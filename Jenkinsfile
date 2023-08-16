pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/PrudhviRajRaavi/curriculum-app/', branch: 'dev')
      }
    }

    stage('error') {
      steps {
        sh 'ls -la'
      }
    }

  }
}