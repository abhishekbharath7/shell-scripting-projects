# 🐚 Shell Scripting Projects

A collection of shell scripts for automating common DevOps tasks.

## 📁 Scripts Included

### 1. AWS Resource Lister

- **File:** `aws-resource-list.sh`
- **Description:** Lists AWS resources (like EC2, S3, etc.) based on the service name you provide.
- **Usage:**
        ./aws_resource_list.sh  <aws_region> <aws_service>
- **Example:**
    ```bash
        ./aws_resource_list.sh us-east-1 ec2

! Note: Make sure your AWS CLI is configured using aws configure.



### 2. GitHub Repository Users Lister

- **File:** `list-users.sh`
- **Description:** Lists users who have access to a GitHub repository using GitHub API.
- **Usage:**
