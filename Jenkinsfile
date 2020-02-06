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
      }
    }
  }
}