# Cruddur - Cloud-Native Social Media Platform

A full-stack social media application built to demonstrate proficiency with AWS cloud services and modern application architecture. This Twitter-like platform features real-time messaging, activity feeds, and user interactions, deployed using a comprehensive suite of AWS technologies.

![Cruddur Graphic](_docs/assets/cruddur-banner.jpg)

![Cruddur Screenshot](_docs/assets/cruddur-screenshot.png)

## Overview

Cruddur is a cloud-native social media application that showcases enterprise-grade AWS implementation patterns. The application allows users to post activities (similar to tweets), engage with content, and communicate through direct messaging.

## Technology Stack

### Frontend

- **React.js** - Modern JavaScript framework for building the user interface
- **CSS3** - Custom styling and responsive design

### Backend

- **Python (Flask)** - RESTful API backend service
- **OpenAPI 3.0** - API documentation and specification

### AWS Services

- **Amazon Cognito** - User authentication and authorization
- **IAM** - Identity and access management, security policies
- **Amazon RDS** - Relational database for persistent data storage
- **AWS Lambda** - Serverless functions for event-driven processing
- **Amazon ECS** - Container orchestration for backend services
- **Application Load Balancer** - Traffic distribution and high availability
- **Amazon VPC** - Network isolation and security
- **CloudWatch** - Monitoring and logging

## Architecture

This project demonstrates:

- **Containerized microservices** architecture using Docker and ECS
- **Serverless computing** patterns with Lambda
- **Secure authentication** flows with Cognito
- **Database management** with RDS PostgreSQL
- **Infrastructure as Code** best practices
- **CI/CD pipeline** implementation
- **Cloud security** with IAM policies and VPC configuration
- **Scalable deployment** using load balancers and auto-scaling

## Project Purpose

This application serves as a portfolio piece demonstrating hands-on experience with:

- Designing and deploying production-ready cloud applications
- Implementing AWS services in real-world scenarios
- Building secure, scalable, and maintainable cloud infrastructure
- Full-stack development with modern technologies

## Key Features

- **User Authentication** - Secure sign-up, sign-in, and account recovery using AWS Cognito
- **Activity Feed** - Create, view, and interact with posts (activities)
- **Direct Messaging** - Real-time messaging between users
- **User Profiles** - Personalized user pages with activity history
- **Search** - Discover content and users across the platform
- **Responsive Design** - Mobile-friendly interface that works across devices

## Getting Started

### Prerequisites

- AWS Account with appropriate permissions
- Docker and Docker Compose
- Node.js and npm
- Python 3.x

### Local Development

Refer to the backend and frontend README files for specific setup instructions:

- [Backend Setup](backend-flask/README.md)
- [Frontend Setup](frontend-react-js/README.md)

## Project Structure

```
├── backend-flask/          # Python Flask API backend
│   ├── app.py             # Main application entry point
│   ├── services/          # Business logic and service layer
│   └── requirements.txt   # Python dependencies
│
├── frontend-react-js/     # React frontend application
│   ├── src/
│   │   ├── components/    # Reusable UI components
│   │   └── pages/         # Application pages/routes
│   └── public/            # Static assets
│
└── _docs/                 # Documentation and assets
```
