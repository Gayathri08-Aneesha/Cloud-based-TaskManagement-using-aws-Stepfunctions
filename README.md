🧠 Cloud-Based Task Management System with AWS Step Functions

This project showcases the development of a serverless, automated task management system using AWS Step Functions, Lambda, and DynamoDB. Designed to streamline and automate business workflows, it demonstrates how cloud-native tools can orchestrate tasks in a scalable, secure, and efficient manner.

🚀 Project Overview

🧩 Workflow Components
ProcessPurchage – Handles purchase task logic.

ProcessRefund – Manages refund operations conditionally.

State Machine – Orchestrates task execution and decision-making using Amazon States Language (ASL).

🛠️ AWS Services Used
AWS Step Functions – Manages and visualizes the state transitions in task workflows.

AWS Lambda – Performs backend logic for each task in a serverless manner.

Amazon DynamoDB – Stores task-related data such as task ID, owner, and status.

Amazon API Gateway (optional) – Provides REST endpoints for invoking the workflow externally.

IAM (Identity and Access Management) – Secures role-based access between services.

Amazon S3 – Stores task attachments and logs.

Amazon CloudWatch – Monitors logs, sets alarms, and provides real-time observability.

📌 How to Use
1. Create Lambda Functions
Deploy ProcessPurchage and ProcessRefund functions with appropriate business logic.

2. Configure IAM Roles
Create and attach a role (e.g., StepFunctionLambdaRole) with required permissions for Lambda and Step Functions.

3. Define the State Machine
Build your workflow using Amazon States Language (ASL) and integrate Lambda functions.

4. Run and Test the Workflow
Trigger executions manually or via API Gateway. Use the console to monitor flow and validate transitions.

5. Analyze Logs and Metrics
Use Amazon CloudWatch to verify outputs, debug issues, and track performance.

🎥 Demo Video
👉 https://youtu.be/ki8rGgxTSCc?feature=shared

🎯 Learning Outcomes
Gained hands-on experience building a serverless workflow.

Understood modular architecture and the role of each AWS component.

Implemented secure access controls using IAM roles.

Used CloudWatch for real-time monitoring and debugging.

Learned how to design and orchestrate logic with Step Functions using ASL.

📬 Feel Free to Contact
For questions, suggestions, or collaboration:

📧 gayathrid2005@gmail.com

