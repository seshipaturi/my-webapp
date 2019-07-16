pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'hostname'
          }
        }
        stage('build2') {
          steps {
            sh 'echo hello'
          }
        }
        stage('buiild3') {
          steps {
            sh 'date'
          }
        }
      }
    }
    stage('Test') {
      steps {
        sh 'mvn clean install'
      }
    }
  }
}