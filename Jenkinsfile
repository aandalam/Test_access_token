pipeline {
  agent any
  stages {
    stage('Dev') {
      steps {
        echo 'Hello Dev'
      }
    }
    stage('Test') {
      steps {
        sh 'mvn clean install'
      }
    }
  }
}