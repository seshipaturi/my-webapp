pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'hostname'
      }
    }
    stage('') {
      steps {
        build 'mvn clean install'
      }
    }
  }
}