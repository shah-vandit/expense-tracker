pipeline {
  agent any
  stages {
    stage('Plan Stage') {
      steps {
        powershell 'echo "Planning"'
      }
    }

    stage('Code Stage') {
      steps {
        powershell 'echo "Coding"'
      }
    }

    stage('Build Stage') {
      steps {
        powershell 'echo "Building"'
      }
    }

    stage('Test Stage') {
      steps {
        powershell 'echo "Testing"'
      }
    }

  }
}