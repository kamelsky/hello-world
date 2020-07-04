pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('Initialize') {
      steps {
        sh 'echo "Hello world"'
        sh 'echo $CUSTOM_ENV'
      }
    }

  }
  environment {
    CUSTOM_ENV = 'CUSTOM_ENVI'
  }
}