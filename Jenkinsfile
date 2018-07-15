pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'echo "Hello world!"'
          }
        }
        stage('') {
          steps {
            sleep 5
          }
        }
      }
    }
    stage('') {
      steps {
        echo 'Another Message'
      }
    }
  }
}