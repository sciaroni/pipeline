pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'ping -c 10 www.google.com'
      }
    }
    stage('test') {
      steps {
        sh 'echo "This is the test step"'
      }
    }
    stage('Deploy') {
      steps {
        sh 'echo "This is the Deploy step"'
      }
    }
  }
}