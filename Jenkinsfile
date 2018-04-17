pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello World!'
      }
    }
    stage('Go Version') {
      steps {
        sh 'java -version'
      }
    }
  }
}