pipeline {
  agent any
  stages {
    stage('Stage1') {
      parallel {
        stage('Stage1') {
          steps {
            sleep 5
          }
        }
        stage('Stage1.1') {
          steps {
            echo 'Stage1.1'
          }
        }
      }
    }
    stage('Stage2') {
      steps {
        echo 'stage 2'
      }
    }
    stage('Stage3') {
      steps {
        echo 'Stage 3'
      }
    }
  }
}