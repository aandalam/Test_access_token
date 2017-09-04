pipeline {
  agent any
  stages {
    stage('Dev') {
      steps {
        sh 'mvn clean install'
      }
    }
    stage('Test') {
      steps {
        echo 'Hello Test'
      }
    }
  }
}