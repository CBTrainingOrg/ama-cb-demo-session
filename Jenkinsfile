pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Say Hello / Print Message') {
      steps {
        echo 'Hello World!'
        sh 'java -version'
      }
    }
  }
  environment {
    message = 'Hello world'
  }
}