---

# ⚙️ 4. Jenkins Basics

## 🔹 What is Jenkins?
Jenkins is an **automation server** used for **Continuous Integration (CI)** and **Continuous Delivery (CD)**.

---

## 🔹 Key Features
- Automates build and testing  
- Integrates with Git, Docker, AWS, etc.  
- Provides dashboards and logs  
- Uses “Pipelines” for end-to-end automation  

---

## 🔹 Jenkinsfile Example
```groovy
pipeline {
  agent any
  stages {
    stage('Build') {
      steps { echo 'Building...' }
    }
    stage('Test') {
      steps { echo 'Testing...' }
    }
    stage('Deploy') {
      steps { echo 'Deploying...' }
    }
  }
}
