Building a CI/CD Pipeline with Docker: From Code to Deployment for a client based in Oil and Gas to automate the process of inspection of structural health of pipelines and windmills using Computer Vision to detect anomalies like corrosion and optimizing the model.

Key Takeaways:

Task 1: Containerizing Spring Boot application with Docker and Docker Compose
● Docker simplifies the application deployment by packaging code and dependencies into a container image.
● Using Dockerfile to define the build process for the Spring Boot application.
● The "Docker Compose" allows multi-container applications to run together using "docker-compose.yml".

Task 2: Set up GitHub Actions pipeline for building Docker image
● GitHub Actions automates CI/CD workflows for repositories.
● Define pipeline steps in .github/workflows to build and test Docker images.
● A successful CI pipeline ensures a production build-ready Docker image.

Task 3: Authenticate and push Docker images to AWS ECR registry with Github Actions**
● AWS ECR (Elastic Container Registry) stores Docker images securely.
● Authenticate pipelines with AWS IAM credentials and configure GitHub Secrets.
● Automate image pushes to ECR from the CI pipeline for reliable storage and versioning.

Task 4: Practice Activity
Reinforce concepts by containerizing an additional application and automating its build process.

Task 5: Set up EC2 to pull and run Docker images from ECR
● Create an IAM role for EC2 service and launch an EC2 instance with the right configurations.
● Install Docker and Docker Compose and Amazon-ecr-credential-helper on EC2 for the environment setup.
● EC2 instances can pull Docker images using the created IAM role for authentication.
● Pull and run Docker images directly from ECR for manual testing.

Task 6: Automate the deployment of the application to EC2 with CD pipeline
● Use SSH keys stored in GitHub Secrets for secure access to the EC2 instance.
● Configure the pipeline to automate deployment by pulling and running Docker containers on EC2.
● Verify the pipeline by testing the complete CI/CD workflow after pushing code changes.

⸻

Additional Resources:
● All necessary ZIP files and the script for installing the EC2 requirements are attached in the Key Takeaways/Resources section of the user interface.


