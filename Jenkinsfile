pipeline {
  agent any
  stages {
    stage('Example') {
      parallel {
        stage('Build 1') {
          steps {
            sh "echo 'Hello, World!' > hello.txt"
            sh "sleep 10"
          }
        }
        stage('Build 2') {
          steps {
            sh "sleep 10"
            sh "cat hello.txt"
          }
        }
      }
    }
  }
}
