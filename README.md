# AWS Resource Tracker

This project provides a bash script for tracking various AWS resources using AWS CLI. The script allows you to monitor the following AWS resources:

- S3 Buckets
- EC2 Instances
- Lambda Functions
- IAM Users

## Prerequisites

Before using the script, you need to have the AWS CLI installed and set up on your machine. If you haven't already done so, you can follow the official guide to install and configure the AWS CLI: [Installing the AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-quickstart.html)

## Usage

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/aljozy/shellscripts.git
   ```

2. Change to the project directory:

   ```bash
   cd shellscripts
   ```

3. Make the script executable:

   ```bash
   chmod +x aws_tracker.sh
   ```

4. Execute the script by providing no arguments:

   ```bash
   ./aws_tracker.sh
   ```

   The script will prompt you to select a resource type to track (S3 Buckets, EC2 Instances, Lambda Functions, IAM Users). After selecting a resource type, it will use the AWS CLI to fetch and display relevant information about the chosen resource.

## Disclaimer

This script interacts with your AWS account using the AWS CLI. Make sure you have appropriate permissions to access the resources you intend to track. Use this script responsibly and only in environments where you have proper authorization.

