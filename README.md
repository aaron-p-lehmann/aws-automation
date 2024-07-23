AWS Setup
=========
This repository is for bash and Python scripts to setup and maintain varioius AWS services.

* ./mfa_aws_env_setup - Open an AWS CLI session

* eks/bash/create_eks_cluster - Creates an eks cluster based on the steps in https://docs.aws.amazon.com/eks/latest/userguide/getting-started-console.html
* eks/bash/eks_functions - functions used for managing eks stuff
* eks/bash/get_eks_arguments - a script to be sourced to parse the command-line arguments passed to create_eks_cluster
* eks/resources - resource files that are used in create_eks_cluster
