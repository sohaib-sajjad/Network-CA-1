# Automated Node.js Deployment (AWS + Docker + GitHub Actions)

This project demonstrates an **automated deployment pipeline** for a simple Node.js web application using **AWS CloudFormation**, **Docker**, and **GitHub Actions**.

Whenever code is pushed to the repository, GitHub Actions automatically builds and redeploys the containerized Node.js app to an AWS EC2 instance.

---

## Technologies Used

* **AWS CloudFormation** – Infrastructure as Code
* **Docker** – Application containerization
* **GitHub Actions** – CI/CD automation
* **Node.js (Express.js)** – Simple backend application

---

## Files in Repository

* `AWS cloudformation template.yml` – Provisions EC2, IAM Role, and Security Group
* `Dockerfile` – Builds the Node.js container image
* `index.js` – Express.js app
* `package.json` – Node dependencies
* `main.yml` – GitHub Actions workflow for deployment

---

## Live Application

You can view the deployed app here:
[**Live Application on AWS EC2**](http://ec2-13-62-105-43.eu-north-1.compute.amazonaws.com/)


## Additional Resources

* **GitHub Repository:** [https://github.com/sohaibsajjad/aws-docker-nodejs-deployment](https://github.com/sohaibsajjad/aws-docker-nodejs-deployment)
* **Video Presentation:** [https://youtu.be/example-presentation-link](https://youtu.be/example-presentation-link)

---
