# Test assigment

Automated CI/CD pipeline that runs upon every push or PR to main branch:

* Builds a simple test application image running on 8080 port using Docker.
* Pushes docker image to ECR.
* Deploys app on AWS EKS cluster using Helm.


Prerequisites:
* EKS cluster running in AWS
* ECR registry, proper IAM configuration in place
* Ensure the AWS_ACCESS_KEY_ID and AWS_SECRET_ACCESS_KEY are configured in your GitHub repository settings.
