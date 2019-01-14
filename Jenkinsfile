pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        echo 'Starting test'
        sh 'mvn test'
      }
    }
    stage('Done') {
      steps {
        echo 'End of tests'
      }
    }
  }
}