pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'cd srishti-app'
        bat 'npm install'
        bat 'npm release'
      }
    }

  }
}