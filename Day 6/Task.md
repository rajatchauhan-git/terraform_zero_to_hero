# TerraWeek Day 6: Terraform Providers



Welcome to **Day 6** of the TerraWeek challenge! 🚀 In today's tasks, we will explore **Terraform providers** and their role in interacting with different cloud platforms or infrastructure services. We will also dive into provider configuration, authentication, and hands-on practice using providers for platforms such as **AWS**, **Azure**, **Google Cloud**, or others.

## Task 1: Learn and Compare Terraform Providers



✨ **Objective**: Learn about Terraform providers and compare their features across different cloud platforms.

📚 **Steps**:

- Spend time learning about Terraform providers and their significance in managing resources across various cloud platforms or infrastructure services.
- Compare the features and supported resources for each cloud platform's Terraform provider to gain a better understanding of their capabilities.

## Task 2: Provider Configuration and Authentication



✨ **Objective**: Explore provider configuration and set up authentication for each provider.

📚 **Steps**:

- Explore provider configuration and authentication mechanisms in Terraform.
- Set up authentication for each provider on your local machine to establish the necessary credentials for interaction with the respective cloud platforms.

## Task 3: Practice Using Providers



✨ **Objective**: Gain hands-on experience using Terraform providers for your chosen cloud platform.

📚 **Steps**:

- Choose a cloud platform (AWS, Azure, Google Cloud, or others) as your target provider for this task.
- Create a Terraform configuration file named `main.tf` and configure the chosen provider within it.
- Authenticate with the chosen cloud platform using the appropriate authentication method (e.g., access keys, service principals, or application default credentials).
- Deploy a simple resource using the chosen provider. For example, if using AWS, you could provision a Virtual Private Cloud (VPC), Subnet Group, Route Table, Internet Gateway, or a virtual machine.

[![image](https://private-user-images.githubusercontent.com/55047333/244675175-6578fa41-b860-4204-a9a2-d40acdcd5a26.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjQ3MzA0NzMsIm5iZiI6MTcyNDczMDE3MywicGF0aCI6Ii81NTA0NzMzMy8yNDQ2NzUxNzUtNjU3OGZhNDEtYjg2MC00MjA0LWE5YTItZDQwYWNkY2Q1YTI2LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA4MjclMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwODI3VDAzNDI1M1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWNkYTU1NTM5ZTlkMmEzOGNjMzU2MjA3YWQ5MGIyNjQ5NjZjNmJiMzcwMGUyYTk2MGUwYWUzZTViZjk1ZjMxMzcmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.1n0NOf0ikis24vlDLKjnRnASjeOozBQO1nmZ1BKSmDo)](https://private-user-images.githubusercontent.com/55047333/244675175-6578fa41-b860-4204-a9a2-d40acdcd5a26.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjQ3MzA0NzMsIm5iZiI6MTcyNDczMDE3MywicGF0aCI6Ii81NTA0NzMzMy8yNDQ2NzUxNzUtNjU3OGZhNDEtYjg2MC00MjA0LWE5YTItZDQwYWNkY2Q1YTI2LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA4MjclMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwODI3VDAzNDI1M1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWNkYTU1NTM5ZTlkMmEzOGNjMzU2MjA3YWQ5MGIyNjQ5NjZjNmJiMzcwMGUyYTk2MGUwYWUzZTViZjk1ZjMxMzcmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.1n0NOf0ikis24vlDLKjnRnASjeOozBQO1nmZ1BKSmDo)

- 🔄 Experiment with updating the resource configuration in your `main.tf` file and apply the changes using Terraform. Observe how Terraform intelligently manages the resource changes.
- Once you are done experimenting, use the `terraform destroy` command to clean up and remove the created resources.