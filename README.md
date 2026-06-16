# AWS CI/CD Pipeline Project

## 🏗️ Project Overview
A complete CI/CD pipeline built on AWS to automatically 
build, test, and deploy a Java web application (vprofile).

## 🏛️ Architecture
Bitbucket (Source) → AWS CodeBuild (Build) → AWS Elastic Beanstalk (Deploy)
Connected via AWS CodePipeline

## ☁️ AWS Services Used
- AWS Elastic Beanstalk - Application hosting
- AWS RDS MySQL - Backend database
- AWS CodeBuild - Build and test
- AWS CodePipeline - CI/CD orchestration
- Amazon S3 - Artifact storage
- IAM - Permissions and roles

## 📁 Project Structure
- 01_Beanstalk - Elastic Beanstalk setup
- 02_RDS - RDS MySQL database setup
- 03_Bitbucket - Source control setup
- 04_CodeBuild - Build configuration
- 05_CodePipeline - Pipeline setup
- 06_Final_Verification - Testing and verification

## ✅ Project Outcome
Successfully built and deployed a Java web application 
using a fully automated AWS CI/CD pipeline.
