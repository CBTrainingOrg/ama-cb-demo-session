pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Say Hello / Print Message') {
      steps {
        echo "Hello ${MY_NAME}!"
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Ameet'
  }
}