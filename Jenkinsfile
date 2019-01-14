pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        echo 'Starting test'
        sh 'mvn test'
      }
    }
    stage('Build') {
      steps {
        echo 'Start building'
        sh 'mvn package'
      }
    }
  }
}