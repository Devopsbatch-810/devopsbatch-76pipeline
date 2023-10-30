pipeline {
  agent any
  stages {
    stage('plan') {
      steps {
        echo 'i have plan to work on cicd'
      }
    }

    stage('code') {
      steps {
        echo 'i have code to work on cicd'
      }
    }

    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'i have build to work on cicd'
          }
        }

        stage('test') {
          steps {
            echo 'i have test to work on cicd'
          }
        }

        stage('reslease') {
          steps {
            echo 'i have release to work on cicd'
          }
        }

        stage('deploy') {
          steps {
            echo 'i have deploy to work on cicd'
          }
        }

        stage('oparate') {
          steps {
            echo 'i have oparate to work on cicd'
          }
        }

      }
    }

  }
}