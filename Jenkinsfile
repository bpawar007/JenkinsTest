pipeline {
  agent any
  stages {
    stage('CheckoutCode') {
      agent any
      steps {
        git(url: 'https://github.com/bpawar007/JenkinsTest', branch: 'main')
      }
    }

  }
}