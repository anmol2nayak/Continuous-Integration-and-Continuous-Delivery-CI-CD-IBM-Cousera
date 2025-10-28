🚀 Continuous Integration and Continuous Delivery (CI/CD) Pipeline Project
📘 Overview

This project demonstrates the complete setup and execution of a Continuous Integration and Continuous Delivery (CI/CD) pipeline using modern DevOps tools. It automates the build, test, and deployment process, ensuring rapid and reliable software delivery.

The system is designed to follow best practices of CI/CD and can be adapted for any microservice or web-based application.

🧩 Key Components

GitHub Actions / Tekton Pipelines — to automate build and deploy workflows.

Docker — for containerizing the application to ensure consistent environments.

Heroku / Cloud Deployment — to deploy the final image seamlessly.

Unit Tests — for ensuring code reliability and preventing regression issues.

⚙️ Project Structure
├── .github/          # CI/CD pipeline configurations (GitHub Actions)
├── .tekton/          # Tekton pipeline definitions
├── service/          # Core application source code
├── tests/            # Automated test scripts
├── Dockerfile        # Build container image
├── requirements.txt  # Python dependencies
├── setup.py          # Package setup
└── Procfile          # Deployment process definition

🛠️ How to Run Locally
# 1. Clone your repo
git clone https://github.com/anmol2nayak/Continuous-Integration-and-Continuous-Delivery-CI-CD-IBM-Cousera.git

# 2. Navigate inside
cd Continuous-Integration-and-Continuous-Delivery-CI-CD-IBM-Cousera

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run tests
pytest

# 5. Build Docker image
docker build -t ci-cd-app .

# 6. Run container
docker run -p 8080:8080 ci-cd-app

🌐 Deployment

The CI/CD pipeline automatically triggers upon every push to the main branch.
It performs the following sequence:

Build and test the application.

Package it into a Docker image.

Deploy it to the configured cloud environment.

💡 Learning Outcomes

Understand the CI/CD workflow from code commit to deployment.

Automate application lifecycle using Tekton / GitHub Actions.

Learn Dockerization and continuous testing in real-world pipelines.

👨‍💻 Author

Anmol Nayak

B.Tech Student | DevOps & Cloud Enthusiast

🏷️ License

This project is created for academic purposes under open educational use.