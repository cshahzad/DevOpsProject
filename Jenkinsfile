pipeline {
  agent any
  stages {
    stage('error') {
      agent {
        node {
          label 'ubuntu'
        }

      }
      steps {
        sh 'df -h'
      }
    }

    stage('win') {
      steps {
        bat 'systeminfo'
      }
    }

  }
}