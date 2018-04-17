pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello World!'
      }
    }
    stage('Go Version') {
      steps {
        sh 'sh \'go version\''
      }
    }
  }
}