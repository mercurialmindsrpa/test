pipeline {
  agent any
  stages {
    stage('Task 1') {
      parallel {
        stage('Action 1') {
          steps {
            echo 'Hello Action 1'
          }
        }
        stage('Action 2') {
          steps {
            echo 'Hello Action 2'
          }
        }
        stage('Action 3') {
          steps {
            echo 'Hello Action 3'
          }
        }
      }
    }
    stage('Task 2') {
      parallel {
        stage('Action 4') {
          steps {
            echo 'Hello Action 4'
          }
        }
        stage('Action 5') {
          steps {
            echo 'Hello Action 5'
          }
        }
      }
    }
    stage('Task 3') {
      parallel {
        stage('Action 6') {
          steps {
            echo 'Hello Action 6'
          }
        }
        stage('Action 7') {
          steps {
            echo 'Hello Action 7'
          }
        }
      }
    }
  }
  environment {
    Variable = 'ValueOfVariable'
  }
}