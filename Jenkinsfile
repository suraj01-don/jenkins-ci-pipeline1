pipeline {
  agent any
  stages {
    stage('Build') { steps { echo 'Task: compile & package | Tool: Maven/Gradle' } }
    stage('Unit and Integration Tests') { steps { echo 'Task: unit+integration tests | Tools: JUnit/TestNG' } }
    stage('Code Analysis') { steps { echo 'Task: static code analysis | Tools: SonarQube/Checkstyle' } }
    stage('Security Scan') { steps { echo 'Task: security scan | Tools: OWASP Dependency-Check/Snyk' } }
    stage('Deploy to Staging') { steps { echo 'Task: deploy to staging | Tools: Docker/AWS EC2' } }
    stage('Integration Tests on Staging') { steps { echo 'Task: staging integration tests | Tools: Selenium/Postman' } }
    stage('Deploy to Production') { steps { echo 'Task: deploy to production | Tools: AWS EC2/Kubernetes' } }
  }
}
