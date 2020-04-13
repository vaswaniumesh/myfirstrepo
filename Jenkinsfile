pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'cd srishti-app && npm install && npm run release'
      }
    }

    stage('Package') {
      steps {
        zip(dir: 'srishti-app\\dist', zipFile: 'srishti-app.zip')
      }
    }

  }
}