pipeline {
  agent any
  stages {
    stage('checkoutcode') {
      steps {
        git(url: 'https://github.com/djamara/mikyonline', branch: 'master')
      }
    }

  }
}