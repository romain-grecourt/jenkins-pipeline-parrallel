pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            echo 'Stage1'
          }
        }
        stage('stage2') {
          steps {
            echo 'from stage2'
          }
        }
      }
    }
    stage('stage3') {
      steps {
        echo 'from stage3'
      }
    }
  }
}