pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'My First Pipeline'
      }
    }
    stage('CheckHostDetails') {
      steps {
        sh 'uname -a;id; docker info'
      }
    }
  }
}