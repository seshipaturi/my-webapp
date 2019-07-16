pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'hostname'
      }
    }
    stage('error') {
      steps {
        sh 'mvn clean install'
      }
    }
  }
}