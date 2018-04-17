pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        echo "Hello ${MY_NAME}!"
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
  parameters {
    string(name: 'Name', defaultValue: 'whoever you are', description: 'Who should I say hi to?')
  }
}