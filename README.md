# CI/CD Pipeline for Data Visualizer Streamlit Web App

This repository showcases the implementation of a **CI/CD pipeline** for a **Streamlit-based data visualizer web app**, utilizing **Docker**, **Jenkins**, and **Ansible** for seamless deployment and automation.

## Features
- **Streamlit Web App**: Provides intuitive data visualizations.
- **CI/CD Pipeline**: Automates build, test, and deployment processes.
- **Containerization**: Ensures consistent environments using Docker.
- **Automation**: Efficient configuration management and deployment with Ansible.

## Tools and Technologies
- **Docker**: For containerizing the application.
- **Jenkins**: To automate the CI/CD process.
- **Ansible**: For deployment and configuration management.
- **Streamlit**: To develop the data visualizer application.

## Workflow Overview
1. **Code Changes**: Developers push updates to the repository.
2. **Build and Test**: Jenkins triggers automated builds and tests.
3. **Containerization**: The app is packaged into a Docker container.
4. **Deployment**: Ansible deploys the containerized app to the server.

## Setup and Usage

### Prerequisites
- **Docker** installed on your system.
- **Jenkins** setup for CI/CD.
- **Ansible** installed for deployment.
- Basic understanding of Streamlit and Python.

### Steps to Reproduce

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/MekhzZ/CI-CD_Pipeline_for_Data_Visualizer_Streamlit_Web_App.git
   cd CI-CD_Pipeline_for_Data_Visualizer_Streamlit_Web_App
   ```

2. **Build the Docker Image**:
   ```bash
   docker build -t data-visualizer .
   ```

3. **Run the Docker Container**:
   ```bash
   docker run -p 8000:7000 data-visualizer
   ```

4. **Access the App**:
   Open your browser and go to `http://localhost:8000`.

5. **CI/CD Pipeline Setup**:
   - Configure Jenkins to build and deploy on code changes.
   - Use Ansible for deployment automation.

## Certificate of Participation
View my certificate from the CI/CD workshop: [Certificate Link](<certificate_link>)

