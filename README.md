Hi 😊 
Welcome to my Cloud Engineering GitHub repository! This is where I showcase various cloud infrastructure projects, with a focus on AWS services, migration strategies, and scalable solutions. Below you will find a collection of real-world projects I've worked on, demonstrating my expertise in cloud architecture, automation, and security best practices.

## Table of Contents

- [About](#about)
- [Technologies Used](#technologies-used)
- [Projects](#projects)
  - [Building a Well-Architected Microservices Application and CI/CD Pipeline with AWS Services](#building-a-well-architected-microservices-application-and-cicd-pipeline-with-aws-services)
  - [Andy’s Car Auction Migration into AWS Cloud](#andys-car-auction-migration-into-aws-cloud)
  - [Migrating and Securing Classroom Infrastructure on AWS for Scalable and Secure CS Department Operations](#migrating-and-securing-classroom-infrastructure-on-aws-for-scalable-and-secure-cs-department-operations)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## About

As a Cloud Engineer, I specialize in designing and deploying secure, scalable, and cost-effective solutions on cloud platforms, particularly AWS. This repository highlights my work on various cloud migrations, including microservices applications, enterprise systems, and university infrastructure.

The projects here focus on:

- Cloud-native architectures (Microservices, Serverless)
- CI/CD pipelines for continuous deployment
- Infrastructure automation with Infrastructure as Code (IaC)
- Cloud migration strategies and security
- High availability and disaster recovery planning

## Technologies Used

- **Cloud Platforms**: AWS (EC2, S3, Lambda, ECS, RDS, etc.), CloudFormation, IAM, VPC
- **CI/CD**: AWS CodePipeline, Jenkins, GitLab CI
- **Automation & IaC**: Terraform, CloudFormation
- **Containerization**: Docker, Kubernetes, ECS
- **Security**: AWS WAF, IAM Policies, KMS
- **Monitoring & Logging**: CloudWatch, Prometheus, Grafana
- **Scripting**: Python, Bash

## Projects

### Building a Well-Architected Microservices Application and CI/CD Pipeline with AWS Services

This project demonstrates the design and deployment of a **microservices application** using a **well-architected framework** on AWS. The application is deployed using **AWS Elastic Beanstalk** and **ECS (Elastic Container Service)** for scalable containerized environments. The project also includes building a robust **CI/CD pipeline** using **AWS CodePipeline** and **CodeBuild** to automate the entire deployment process.

**Key Features:**
- Microservices architecture using Docker containers
- Automated CI/CD pipeline with AWS CodePipeline
- Infrastructure as Code using Terraform
- Integration with AWS services: S3, RDS, Elastic Load Balancer (ELB)
- Secure API Gateway with AWS Lambda and Cognito for authentication

**How to use:**
1. Clone the repository.
2. Configure your AWS credentials using the AWS CLI.
3. Customize your application configuration in the `terraform/main.tf` file.
4. Run `terraform apply` to provision the infrastructure.
5. Use the provided deployment scripts to deploy microservices.

### Andy’s Car Auction Migration into AWS Cloud

**Andy’s Auctions**, a used car auction business, faced difficulties when recent lockdowns reduced the number of customers attending physical auctions. In response, they decided to move their business systems to AWS, establishing a stronger online presence and improving scalability.

This migration project involved transferring the auction platform from on-premise infrastructure to the cloud, ensuring high availability, security, and disaster recovery capabilities.

**Key Features:**
- **Lift and Shift** migration to AWS for scalable infrastructure
- **Amazon EC2** instances for backend services
- **RDS** for secure database hosting
- **S3** for secure file storage
- **CloudWatch** for monitoring and alarms
- **Elastic Load Balancer** for distributing traffic

**How to use:**
1. Clone the repository.
2. Set up your AWS credentials and configure the AWS CLI.
3. Follow the migration strategy outlined in the project documentation for specific steps on how the auction platform was migrated.
4. Use CloudFormation or Terraform scripts to replicate the architecture.

### Migrating and Securing Classroom Infrastructure on AWS for Scalable and Secure CS Department Operations

In this project, a university's **Computer Science department** needed to migrate from an aging, insecure, and unreliable on-premise server to a more scalable and secure infrastructure on **AWS**. The infrastructure hosted sensitive data, such as gradebooks, and faced performance challenges due to increased traffic.

The migration process involved creating a secure and scalable solution that protects sensitive data and ensures high availability for web portals and gradebook applications.

**Key Features:**
- **EC2 instances** for gradebook and web portal hosting
- Use of **VPC** with proper security group and NACL configurations
- **AWS KMS** for data encryption
- **IAM roles** and **AWS Shield** for secure user access
- **CloudWatch** for monitoring and automated alerts
- **Auto Scaling** for handling traffic spikes to the web portal

**How to use:**
1. Clone the repository.
2. Review the architecture and migration steps in the project documentation.
3. Follow the deployment and configuration scripts to move the system to AWS.
4. Ensure that all IAM roles and policies are configured properly for enhanced security.

## Setup and Installation

To get started with the code in this repository, follow these general installation steps:

1. **Clone the repository:**

```bash
git clone https://github.com/Mbitajeff/cloud-engineer-repo.git
```

2. **Install prerequisites:**

   - AWS CLI
   - Terraform (for IaC)
   - Docker (for containerized applications)
   - Kubernetes (if applicable)
   - Jenkins or AWS CodePipeline (for CI/CD)

3. **Configure your cloud environment:**

   - Set up your AWS credentials using the `aws configure` command.
   - Set up the required AWS services based on project-specific instructions.

4. **Run the setup scripts or manual steps as outlined in individual project directories.**

## Usage

Each project in this repository contains detailed usage instructions in its respective directory. Follow the documentation provided with each project to deploy, configure, or troubleshoot the cloud environments.

## Contributing

Contributions are welcome! If you have suggestions, improvements, or bug fixes, feel free to fork the repository and create a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

## License

This repository is licensed under the [MIT License](LICENSE).

## Contact

For any questions or inquiries, please feel free to contact me at:

- Email: Jeffmbita69@gmail.com(mailto:jeffmbita69@gmail.com)
- LinkedIn: JeffMbita(https://www.linkedin.com/in/jeff-mbita-a91672241/)

---

Feel free to modify any section to suit the specific tools or services you’ve used in these projects! This format highlights the core projects and gives a professional overview of your cloud engineering skills.
