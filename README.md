# Efficient Code Review Automation

## Project Overview
The "Efficient Code Review Automation" project aims to streamline and automate the code review process using AWS CodeGuru. Traditionally, developers had to manually upload their code to an S3 bucket and initiate a pull request to get code recommendations from AWS CodeGuru. This project eliminates the manual steps and provides a seamless experience for developers.

## Purpose
To automate the code review process by providing a web-based application where users can upload their Java or Python code, and the system handles the rest. The project automates the following tasks:
1. Accepts uploaded code files.
2. Uploads the files to an S3 bucket.
3. Automates the pull request process to AWS CodeGuru’s API.
4. Retrieves and processes the code review recommendations.
5. Sends the recommendations back to the frontend for display.

## Role
As a **Backend Developer**, my responsibilities included:
- Developing middleware that handles the following tasks:
  1. Accepting uploaded code files from the frontend.
  2. Uploading the code files to an S3 bucket.
  3. Automating the pull request process to AWS CodeGuru’s API.
  4. Retrieving and processing the code review recommendations from AWS CodeGuru.
  5. Sending the recommendations back to the frontend for user display.

## Tech Stack
- **NodeJS**: Used for backend development to handle the API requests and interact with AWS services.
- **ReactJS**: Used for the frontend to create a user-friendly interface for code uploads and displaying review results.
- **AWS**: Utilized AWS services like S3 for file storage and AWS CodeGuru for automated code reviews.

## Folder Structure
- **backend**: Contains the backend code responsible for:
  - Accepting uploaded code files.
  - Uploading the files to an S3 bucket.
  - Automating interactions with AWS CodeGuru's API.
  - Retrieving code review recommendations and sending them to the frontend.
  
- **code reviewer**: Contains the frontend code for:
  - Creating a web-based interface where users can upload their code.
  - Displaying the results of the code review from AWS CodeGuru.

Ensure that your AWS credentials are set up correctly. You will need to configure AWS access keys for the project to interact with AWS services like S3 and AWS CodeGuru. Replace any sensitive information (e.g., API keys) with your own credentials.

If file structure changed pls update bash commands

## Setup Instructions

### 1. Clone the repository
Clone this repository to your local machine:
```bash
git clone <repository-url>
cd <repository-folder>

cd backend
npm install

cd ../code-reviewer
npm install

cd backend
npm start


