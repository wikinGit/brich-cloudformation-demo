# AWS CloudFormation Project

## Overview

This project utilizes a pre-defined AWS CloudFormation template to provision and manage a comprehensive infrastructure setup. The resources provisioned are designed to support a web application with robust backend services and secure data management.

## Provisioned Resources

The AWS CloudFormation template provisions the following resources:

- **AWS Internet Gateway**
  - Facilitates internet access for the Amazon VPC.

- **Amazon VPC**
  - Configured with load balancers for both frontend and backend networks to ensure efficient traffic distribution.

- **Amazon EC2 Instances**
  - Two instances are set up to handle web application and database services.

- **Amazon RDS Instance**
  - A MySQL database instance is provisioned for reliable data storage and management.

- **Amazon S3 Bucket**
  - Used for storing uploaded files, ensuring scalable and secure file storage.

- **Amazon System Manager**
  - Provides secure HTTPS connections for managing resources.

- **AWS Identity and Access Management (IAM)**
  - Roles and policies are configured to grant necessary permissions for resource access and management.

- **Security Groups and Subnets**
  - Implemented to control network access and enhance security across the infrastructure.

## Usage

This setup is ideal for deploying a web application that requires a scalable and secure backend infrastructure. The resources can be managed and monitored through the AWS Management Console or CLI.

## Contact

For questions, support, or further information, please contact:

- **Name:** Warren Ikin
- **Email:** [wikin@bigpond.net.au](mailto:wikin@bigpond.net.au)
- **Mobile:** 0417006497

## License

This project is licensed under [License Name]. See the LICENSE file for more details.

## Acknowledgments

We extend our gratitude to all contributors and open-source projects that have facilitated the development of this infrastructure.
