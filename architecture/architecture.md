# Architecture

## CI/CD Pipeline Architecture

## Flow
Bitbucket (Source) → AWS CodeBuild (Build) → AWS Elastic Beanstalk (Deploy)
Connected via AWS CodePipeline

## AWS Services
- Bitbucket: Source code repository
- AWS CodePipeline: Orchestrates the CI/CD flow
- AWS CodeBuild: Builds and tests the application
- AWS Elastic Beanstalk: Hosts and deploys the application
- AWS RDS MySQL: Backend database
- Amazon S3: Stores build artifacts
- IAM: Manages permissions and roles