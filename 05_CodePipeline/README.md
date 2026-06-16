# 05 - AWS CodePipeline Setup

## Overview
Created AWS CodePipeline to connect all services and automate the CI/CD flow.

## Steps Performed
- Created pipeline (vprocicdpipeline)
- Source Stage: Bitbucket (aws-ci branch)
- Build Stage: AWS CodeBuild (vproppbuild)
- Deploy Stage: AWS Elastic Beanstalk (vprofile-prod1133)
- Added IAM policy for Beanstalk access
- Pipeline executed successfully
- All 3 stages completed with Succeeded status