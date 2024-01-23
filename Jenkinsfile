pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Building the application...'
          }
        }

        stage('issue1') {
          steps {
            echo 'this is issue1'
          }
        }

      }
    }

    stage('Test') {
      steps {
        echo 'Running Tests..'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying the application'
      }
    }

  }
}