# CI/CD Pipeline Demo Project

## Overview
This project demonstrates a **CI/CD pipeline** using **GitHub Actions** and **AWS**. It automates building, testing, and deploying a Python GUI demo application, showcasing cloud deployment and continuous integration practices.

## Project Workflow
1. **Python Demo Application**  
   - Created a simple Python GUI using Tkinter to simulate the application.  
   - ![Python GUI Demo](images/python-gui.png)

2. **Git & GitHub Setup**  
   - Initialized Git locally and pushed the project to GitHub.  
   - Resolved merge conflicts when syncing with the remote repository.  
   - ![GitHub Repository](images/repo-overview.png)

3. **GitHub Actions CI/CD**  
   - Created a workflow to automatically build, test, and deploy the app on every push to `main`.  
   - Verified workflow runs and ensured automated deployments.  
   - ![GitHub Actions Workflow](images/workflow-success.png)

4. **AWS Deployment**  
   - Configured AWS (EC2/S3) for hosting the application.  
   - Linked GitHub Actions to deploy updates automatically after successful tests.  
   - ![AWS Deployment](images/aws-deployment.png)

5. **Verification**  
   - Tested Python GUI locally and on AWS to confirm correct deployment.  
   - Made multiple commits to validate the CI/CD pipeline automation.

## Technologies Used
- **Version Control:** Git, GitHub  
- **CI/CD:** GitHub Actions  
- **Cloud Platform:** AWS (EC2/S3)  
- **Programming Language:** Python (Tkinter GUI)  

## Author
Sanita (Pixel) – Cloud Internship Project at Codec Technology
