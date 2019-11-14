pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh 'pip3 install -e ".[dev]"'
      }
    }
  }
}