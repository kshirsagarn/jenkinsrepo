pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh '''pwd
         date'''
          }
        }

        stage('Test') {
          steps {
            echo 'continue'
          }
        }

      }
    }

    stage('Depoy to Test') {
      steps {
        sleep 10
      }
    }

    stage('Deploy to prod') {
      steps {
        sh 'ls'
      }
    }

  }
}