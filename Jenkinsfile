pipeline {
  agent any
  stages {
    stage('Dev') {
      steps {
        echo 'I want to Develop'
      }
    }

    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'I want build'
          }
        }

        stage('test') {
          steps {
            echo 'I want to test'
          }
        }

        stage('deploy') {
          steps {
            echo 'i want to deploy'
          }
        }

      }
    }

  }
}