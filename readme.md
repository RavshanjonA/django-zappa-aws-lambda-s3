# Zappa AWS Lambda S3 Project

This project demonstrates how to deploy a Django application using **Zappa** to **AWS Lambda** with **S3** for static files and media handling.

## Project Overview

This repository is focused on setting up and deploying a Django application to AWS Lambda using the Zappa framework. The project includes:

- **Django**: The web framework used to build the application.
- **Zappa**: To manage the deployment of the Django app to AWS Lambda.
- **AWS S3**: Used to store static files and media.
- **AWS Lambda**: To run the serverless Django application.

## Features

- Serverless Django app hosted on AWS Lambda.
- Static and media file management using AWS S3.
- Configuration through environment variables using `.env`.
- Scalable and cost-efficient deployment using AWS.

## Prerequisites

Before deploying the project, ensure that you have the following:

- **AWS Account** with Lambda and S3 permissions.
- **AWS CLI** configured with access keys.
- **Python 3.12** installed.
- **Zappa** installed globally.

```bash
pip install zappa
```
- **Update Zappa Credentials**: Section on how to change AWS credentials in Zappa and the AWS CLI.

- **Deploy and Update Commands**: Detailed steps for deploying and updating with `zappa deploy` and `zappa update`.
  