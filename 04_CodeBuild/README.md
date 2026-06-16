# 04 - AWS CodeBuild Setup

## Overview
Configured AWS CodeBuild to fetch source code from Bitbucket, build the application and store artifact in S3.

## Steps Performed
- Created S3 bucket for artifacts (awscicdvproartifact)
- Created CodeBuild project (vproppbuild)
- Connected Bitbucket repository via AWS Connection
- Source: Bitbucket (aws-ci branch)
- Operating System: Ubuntu
- Runtime: Standard
- Image: aws/codebuild/standard:7.0
- Created buildspec.yml with Maven build commands
- Build completed successfully
- Artifact uploaded to S3