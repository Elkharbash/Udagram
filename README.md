
# Udagram
Udagram was designed to showcase my skills on how to use AWS CloudFormation to deploy and manage a a high-availability web app using CloudFormation

- [Screenshots](https://github.com/Elkharbash/Udagram/blob/main/Udagram%20Project.jpeg)


## Authors

- [Nabel Elkharbash](https://github.com/Elkharbash)


## Features
The project provides the following features:

- Deploy a web application using AWS CloudFormation
- Use AWS EC2 instances and Load Balancers to create a highly available environment
- Implement security best practices, such as secure communication over HTTPS and secure storage of sensitive data
- Use CloudFormation to manage infrastructure and deployments


## Technologies Used
The project is built using the following technologies:

- AWS CloudFormation for infrastructure as code
- AWS EC2 instances for virtual servers
- AWS Load Balancers for load balancing and high availability
- AWS RDS for the database
- AWS S3 for storing static content
- AWS IAM for access management
- Bash scripts for automation
## Installation

To deploy a high-availability web application using CloudFormation, follow these steps:

1. Clone the repository from GitHub:
```bash
git clone https://github.com/Elkharbash/Udagram.git
```
2. Set up an AWS account and create a new IAM user with the necessary permissions.

3. Set up the AWS CLI on your local machine and configure your credentials.

4. Modify the ```create.sh``` and ```update.sh``` scripts to include the correct AWS region, VPC, subnets, and other configuration parameters.

5. Execute the ```create.sh``` script to create the CloudFormation stack.

6. Access the web application using the Load Balancer DNS name.
    
