pipeline {
  agent any
  stages {
    stage('init') {
      steps {
        sh 'rm -rf node_modules/'
      }
    }

    stage('build') {
      steps {
        sh '''node -v
npm install'''
      }
    }

  }
}