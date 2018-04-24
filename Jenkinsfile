pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'My First Pipeline'
      }
    }
    stage('Status') {
      steps {
        sh 'uname -a'
      }
    }
  }
}