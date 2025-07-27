# 🐚 Shell Scripting Projects

A collection of shell scripts for automating common DevOps tasks.

## 📁 Scripts Included

### 1. 🔍 AWS Resource Lister

- **File:** `aws-resource-list.sh`
- **Description:** Lists AWS resources (like EC2, S3, etc.) based on the service name you provide.
- **Usage:**
    ```bash
        ./aws_resource_list.sh  <aws_region> <aws_service>
    ```
    
- **Example:**
    ```bash
        ./aws_resource_list.sh us-east-1 ec2
    ```

⚠️ Note: Make sure your AWS CLI is configured using aws configure.



### 2. 👥 GitHub Repository Users Lister

- **File:** `list-users.sh`
- **Description:** Lists all GitHub users (collaborators) with `read (pull)` access to a repository you specify.
- **Usage:**

  Export your GitHub credentials as environment variables:

     ```bash
            export username="your_github_username"
            export token="your_personal_access_token"
     ```
     ```bash
        ./list-users.sh <repo_owner> <repo_name>
     ```
     
- **Example:**
    ```bash
         ./list-users.sh devops-abhishek shell-scripting-projects
    ```

    This will list all users with read access to the repository devops-abhishek/shell-scripting-projects.

⚠️ Note: Requires a GitHub Personal Access Token (PAT).
