# AWS Web App Using Amplify, Lambda, DynamoDB, and API

## Project Overview
This project is a serverless web application built using AWS services including Amplify, Lambda, DynamoDB, and API Gateway. The application follows a structured workflow where the frontend is deployed using Amplify, backend logic is handled by Lambda, data is stored in DynamoDB, and API Gateway is used to connect the frontend with backend services. AWS IAM (Identity and Access Management) is used to manage permissions and security across services.

---

## Steps to Build the Application

### 1. Creating the App in AWS Amplify
AWS Amplify is used to host and manage the frontend of the application. It provides a seamless way to deploy and manage a web application with built-in CI/CD capabilities.

**Steps:**
- Created an Amplify app and initialized the environment.
- Configured hosting settings and connected to a repository (optional for local development).
- Deployed the initial frontend setup.

<img width="1280" alt="Screenshot 2025-02-18 at 23 03 01" src="https://github.com/user-attachments/assets/2a1fdfae-4e3f-486d-b06b-f444bec16410" />


---

### 2. Writing Backend Logic with AWS Lambda
Lambda is used to process requests, perform business logic, and interact with DynamoDB. This step involves creating a Lambda function and writing the necessary code in Python.

**Steps:**
- Created a new Lambda function in AWS using Python.
- Wrote code to handle requests and process data.
- Configured IAM permissions to allow Lambda to interact with DynamoDB and API Gateway securely.
- Assigned appropriate execution roles and policies.

<img width="1280" alt="Screenshot 2025-02-18 at 23 04 15" src="https://github.com/user-attachments/assets/944754c5-67a0-49ab-8043-6d5b564182b4" />


---

### 3. Setting Up DynamoDB for Data Storage
DynamoDB serves as the database to store structured data for the application. It provides scalable and managed NoSQL storage.

**Steps:**
- Created a DynamoDB table with a primary key.
- Defined necessary attributes and indexes.
- Configured read and write capacity settings.

<img width="1280" alt="Screenshot 2025-02-18 at 23 03 50" src="https://github.com/user-attachments/assets/a12d4c71-e347-4108-9ec2-d1a13baa3a69" />

---

### 4. Connecting Lambda and DynamoDB Using API Gateway
API Gateway acts as the intermediary that enables communication between the frontend (Amplify) and backend (Lambda + DynamoDB). IAM was used to configure access control and secure the API interactions.

**Steps:**
- Created an API using API Gateway.
- Connected the API to the Lambda function.
- Defined request and response mappings.
- Configured IAM roles to allow secure API-Lambda communication.

<img width="1280" alt="Screenshot 2025-02-18 at 23 05 09" src="https://github.com/user-attachments/assets/5f062005-d475-4f46-bb8a-665041033513" />


---

### 5. Merging and Deploying Everything to AWS Amplify
Once the backend and database were set up, everything was integrated into the frontend and deployed back into Amplify.

**Steps:**
- Integrated API calls in the frontend to interact with Lambda.
- Deployed final changes to AWS Amplify.
- Verified application functionality.

<img width="1280" alt="Screenshot 2025-02-18 at 23 03 21" src="https://github.com/user-attachments/assets/a1f4e919-da34-447d-974d-08bbe8ad4f06" />
<img width="1280" alt="Screenshot 2025-02-18 at 23 03 24" src="https://github.com/user-attachments/assets/84fc5966-4fa0-45ae-aff8-acc519b696d5" />


---

## Conclusion
This project successfully utilizes AWS services to create a scalable and serverless web application. The combination of Amplify, Lambda, DynamoDB, and API Gateway ensures an efficient and fully managed infrastructure for web applications. IAM played a crucial role in managing permissions and securing interactions between services.

Feel free to explore the repository and use the provided screenshots for reference!

---

## Technologies Used
- AWS Amplify
- AWS Lambda (Python)
- Amazon DynamoDB
- Amazon API Gateway
- AWS IAM (Identity and Access Management)
- JavaScript / Python (depending on Lambda implementation)

