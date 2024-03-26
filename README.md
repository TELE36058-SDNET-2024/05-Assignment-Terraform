# 05-Assignment-Terraform

Resources 
* https://github.com/hashicorp/learn-terraform-cloud?tab=readme-ov-file
* https://github.com/terraform-linters/tflint
* https://developer.hashicorp.com/terraform/tutorials/automation/github-actions
* https://github.com/hashicorp/tfc-workflows-github


# Assignment: Building a Secure and Scalable Cloud Infrastructure with Terraform Cloud and GitHub Actions

## Overview
In this assignment, you will design, implement, and manage a complex cloud infrastructure using Terraform, with the workflow automated through GitHub Actions. This project will demonstrate your ability to utilize Terraform Cloud (or Spacelift) for infrastructure as code (IaC) management, apply best practices in code modularity, ensure security through encryption, and adopt appropriate naming and tagging schemes. Your task is to showcase a sophisticated cloud environment setup that could serve as a backbone for real-world applications.

## Objectives
- **Cloud Environment Setup:** Choose a cloud provider (AWS, GCP, or Azure) and design a multi-layered architecture that includes, but is not limited to, VPCs, subnets, routing, load balancers, compute instances, and DNS configurations.
- **IaC Management:** Utilize Terraform Cloud or Spacelift to manage and apply your Terraform configurations. Highlight how you leverage these tools for team collaboration, state management, and applying changes.
- **CI/CD Pipeline:** Implement a CI/CD pipeline using GitHub Actions that automates the testing and deployment of your Terraform configurations.
- **Modularity and Reusability:** Your Terraform code must be modular, allowing for easy reuse and adjustments. Split your infrastructure into logical modules (e.g., networking, compute, database) and demonstrate how they can be instantiated with different configurations.
- **Security and Compliance:** Ensure your infrastructure adheres to security best practices, including the use of encrypted data storage and transmission, secure access management, and adherence to the principle of least privilege.
- **Naming, Tagging, and Documentation:** Develop a consistent naming and tagging scheme for your resources, aiding in resource management, cost tracking, and compliance. Additionally, your codebase should be well-documented, explaining the purpose of modules, inputs, and outputs.

## Deliverables
1. **GitHub Repository:** All your code and documentation should be hosted in a GitHub repository with clear instructions in the README on how to deploy the infrastructure.
2. **Architecture Diagram:** Provide a detailed architecture diagram of your cloud setup, showcasing the relationships between different components.
3. **CI/CD Workflow:** Include the GitHub Actions workflow file (.github/workflows) in your repository, demonstrating the steps for infrastructure linting, planning, and applying.
4. **Demonstration Video:** Submit a short video (3-5 minutes) walking through your infrastructure setup, the code structure, and a demonstration of the CI/CD pipeline in action.
5. **Reflection Report:** Write a brief report (1-2 pages) reflecting on your design choices, challenges encountered, and how you ensured your infrastructure is scalable, secure, and cost-effective.

## Evaluation Criteria
- **Complexity and Scalability:** How sophisticated and scalable is the cloud environment setup?
- **Best Practices:** Adherence to Terraform best practices, including modularity, reusability, and code organization.
- **Security Measures:** Implementation of security best practices and compliance measures.
- **CI/CD Pipeline Efficiency:** The effectiveness of the CI/CD pipeline in automating deployment tasks.
- **Documentation and Presentation:** Quality of the documentation, architecture diagram, demonstration video, and reflection report.

This assignment encourages you to explore advanced cloud infrastructure concepts, apply best practices in IaC, and harness the power of automation with CI/CD pipelines. It's an opportunity to build a foundational skill set that is highly valued in the field of cloud computing and DevOps.
