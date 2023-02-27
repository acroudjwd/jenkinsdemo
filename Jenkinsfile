pipeline {
  agent any
  stages {
    stage('checkout code') {
      steps {
        git(url: 'https://github.com/MarlonDemas/curriculum-app.git', branch: 'dev')
      }
    }

    stage('shell') {
      steps {
        sh 'ls -la'
      }
    }

  }
}