pipeline {
  agent any
  stages {
    stage('Dev') {
      steps {
        echo 'Welcome to devlopers point'
      }
    }

    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Welcome to Building point'
          }
        }

        stage('Test') {
          steps {
            echo 'Welcome to Testing point'
          }
        }

        stage('Deploy') {
          steps {
            echo 'Welcome to Deployment stage'
          }
        }

      }
    }

  }
}