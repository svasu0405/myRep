pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh 'hello build'
          }
        }
        stage('build2') {
          steps {
            echo 'hello'
          }
        }
      }
    }
    stage('test') {
      steps {
        echo 'hello test'
      }
    }
  }
}