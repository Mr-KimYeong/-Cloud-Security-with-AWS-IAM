# -Cloud-Security-with-AWS-IAM
A hands-on project showcasing how to manage AWS resources securely using IAM. This includes creating users, defining IAM policies with JSON, and using user groups to control permissions. 

# AWS IAM Cloud Security Project

## Overview
This project demonstrates the use of **AWS Identity and Access Management (IAM)** to manage users, groups, and permissions in a cloud environment. The focus is on securely controlling access to AWS resources, with a particular emphasis on setting up **IAM policies**, **user groups**, and **tags** for resource organization.

### Key Features:
- **IAM Users & Groups**: Created users and grouped them for better permission management.
- **IAM Policies**: Configured JSON policies to control access to AWS resources.
- **Account Alias**: Created a friendly sign-in URL for easy access.
- **Resource Tagging**: Used tags for organizing EC2 instances based on environment (Production/Development).
- **Testing Policies**: Validated policies by testing access controls on EC2 instances.

## Project Setup

### Prerequisites:
- AWS Account
- Basic understanding of IAM concepts in AWS
- Access to AWS Console

### Steps Taken:
1. **Created IAM Policies**: Defined permissions allowing access to specific resources (e.g., development EC2 instance).
2. **Managed IAM Groups**: Assigned the policies to user groups for easier management.
3. **Testing Policies**: Ensured that users can access only the resources defined in their group policy.

## Usage
To test IAM policies:
1. Log in as an IAM user.
2. Test access to different EC2 instances based on policy restrictions.

## Conclusion
This project provides an in-depth understanding of managing access in AWS environments using IAM. It highlights the importance of structured policy management, resource tagging, and testing to ensure the correct permissions are applied.

## License
This project is licensed under the MIT License.


