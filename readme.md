

# The User Management System Final Project

## Project Overview

The **User Management System** project simulates a real-world software development environment, providing an opportunity to enhance user management features, collaborate with teammates, and gain hands-on experience with various aspects of backend development. My primary focus was implementing the **Profile Picture Upload** feature using **Minio**, alongside other improvements to the user management system.

This README highlights the features I implemented, provides an overview of the system, and includes instructions for deploying the system via Docker.

---

## Features Implemented

### 1. Profile Picture Upload with Minio

**Summary**:  
This feature allows users to upload and manage their profile pictures, leveraging Minio, a high-performance distributed object storage system compatible with Amazon S3 APIs. Below are the key components of this implementation:

#### Key Aspects of the Implementation:
- **API Endpoint Creation**:
  - Developed a new API endpoint for handling profile picture uploads.
  - Ensured secure handling of files with validation and error handling.
  
- **Minio Integration**:
  - Configured Minio for secure storage of profile pictures.
  - Integrated Minio to both upload and retrieve user profile pictures, providing a scalable solution.
  
- **User Profile Update**:
  - Updated the user profile management system to store and display the URL for the profile picture.
  - Modified the API to fetch and display the profile picture URL from Minio.

### 2. Additional Features
- **Nickname Generation**:
  - Enhanced the nickname generation feature, allowing users to update and select unique nicknames.
  
- **Account Upgrades**:
  - Enabled users to verify their profile and upgrade their account to **PRO** status.

---

## Quality Assurance (QA)

During the development process, I identified and resolved 5 QA issues, which were logged on GitHub. These issues involved bugs related to:
- User authentication
- Profile management
- File handling

Each issue was resolved to improve system stability and functionality.

---

## DockerHub Deployment

The project is fully deployed on DockerHub, making it easy to run a containerized version of the system. The Docker image has been tested and ensures smooth deployment.

### DockerHub Repository Link:
[**DockerHub Repository**](https://hub.docker.com/r/trinadravi/user_management/tags)



### Conclusion

This project has been a valuable experience in enhancing my skills in backend development, cloud storage integration, and Docker containerization. Implementing the Profile Picture Upload feature with Minio was a particularly rewarding challenge, and I'm proud of the improvements made to the User Management System. The project has given me hands-on experience with real-world software development, which will be invaluable in future projects.

### Reflection

A detailed reflection document outlining my experience, contributions, and the challenges I faced during the project is attached in the submission.
