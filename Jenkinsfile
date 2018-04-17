pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        echo 'echo "Hello ${MY_NAME}!"'
      }
    }
    stage('Go Version') {
      steps {
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Jason'
  }
}