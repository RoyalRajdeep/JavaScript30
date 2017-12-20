pipeline {
  agent {
    node {
      label 'node'
    }
    
  }
  stages {
    stage('Test') {
      steps {
        echo 'Hello From First Stage'
      }
    }
  }
  environment {
    prod = 'prod'
    stage = 'stage'
  }
}