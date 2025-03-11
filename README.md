🚀 Automating Pull Requests Using Jenkins

📌 Project Overview
This project demonstrates how to automate the process of **building, testing, and deploying** pull requests (PRs) using **Jenkins**. The pipeline automatically triggers whenever a new PR is created or merged in the GitHub repository.

## 🛠️ Technologies Used
- **Jenkins**: CI/CD automation tool
- **Git & GitHub**: Version control and repository hosting
- **GitHub Webhooks**: Triggers Jenkins builds on PR events
- **AWS EC2**: Hosting Jenkins server

## 📂 Project Structure
```
DevOpsJenkinsProject/
│── Jenkinsfile     # Defines the CI/CD pipeline
│── README.md       # Project documentation (this file)
```

## 🔧 Jenkins Pipeline Configuration
### 📜 **Jenkinsfile**
The Jenkins pipeline consists of four stages:
1. **Clone Repository** → Pulls the latest code from GitHub.
2. **Build** → Simulates the build process.
3. **Test** → Runs test cases (mocked in this demo).
4. **Deploy** → Deploys the application (simulated).

## 📌 Author


---

💡 *This project is a demonstration of PR automation using Jenkins in a DevOps workflow.*
