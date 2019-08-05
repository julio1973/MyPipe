pipeline {
  agent any
  stages {
    stage('Develop') {
      steps {
        echo 'init'
      }
    }
    stage('Test') {
      steps {
        sh 'touch test.txt'
      }
    }
    stage('Production') {
      steps {
        echo 'done'
      }
    }
  }
}