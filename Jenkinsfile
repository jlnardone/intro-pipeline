pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        echo "Hello ${MY_NAME}!"
        echo "${TEST_USER_USR}"
        echo "${TEST_USER_PSW}"
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
    TEST_USER = credentials('test-user')
  }
  parameters {
    string(name: 'Name', defaultValue: 'whoever you are', description: 'Who should I say hi to?')
  }
}