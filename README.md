# CI/CD Pipeline Demo Project

## Overview
This project demonstrates a **CI/CD pipeline** using **GitHub Actions** and **AWS Elastic Beanstalk**. It automates building, testing, and deploying a Python **Flask application**, showcasing cloud deployment and continuous integration practices.

---

## Project Workflow

### 1. Python Flask Application
- Developed a Flask backend application (`app.py`) to simulate a web service.
- Handles HTTP requests and responses as part of the demo.
- [Flask Application]<img width="841" height="141" alt="Image" src="https://github.com/user-attachments/assets/2dc2a0b8-6b49-4daf-940e-060b0c70264c" />  

### 2. Git & GitHub Setup
- Initialized a Git repository locally and pushed the code to GitHub.
- Resolved merge conflicts and synced with the remote repository.

### 3. CI/CD Pipeline with GitHub Actions
- Configured `.github/workflows/ci-cd-demo.yml` to:
  - Install dependencies from `requirements.txt`.
  - Run automated tests.
  - Deploy the application to AWS after successful tests.
- Verified workflow execution directly in the GitHub Actions tab.
- [GitHub Actions Workflow]<img width="1428" height="180" alt="Image" src="https://github.com/user-attachments/assets/a6e3a50d-5383-4e64-809e-dcafb5151873" />

### 4. AWS Deployment
- Configured AWS Elastic Beanstalk environment to host the Flask application.
- Linked GitHub Actions workflow to deploy automatically on each push to `main`.
- Verified the live deployment.
- ![AWS Elastic Beanstalk](images/aws-deployment.png)

### 5. Verification
- Accessed the live Flask application via the deployed URL.
- Ensured the CI/CD pipeline works correctly with multiple commits.
- ![Live Application](images/live-app.png)

---

## Technologies Used
- **Version Control:** Git, GitHub  
- **CI/CD:** GitHub Actions  
- **Cloud Platform:** AWS Elastic Beanstalk  
- **Programming Language:** Python (Flask)  

---

## Author
Sanita Gaikwad – Cloud Internship Project at Codec Technology
