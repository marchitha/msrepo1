pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            sh 'echo "step1"'
            echo 'step2'
          }
        }

        stage('stage2') {
          steps {
            sh 'echo "stage2 of step1"'
          }
        }

      }
    }

  }
}