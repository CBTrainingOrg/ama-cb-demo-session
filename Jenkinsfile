pipeline {
  agent none
  stages {
    stage('Say Hello / Print Message') {
      steps {
        echo 'Hello World!'
      }
    }
    stage('error') {
      steps {
        sh 'java -version'
      }
    }
  }
  environment {
    message = 'Hello world'
  }
}