pipeline {
  agent any
  stages {
    stage('ubuntu') {
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
      agent {
        node {
          label 'windows'
        }

      }
      steps {
        bat 'systeminfo'
      }
    }

  }
}