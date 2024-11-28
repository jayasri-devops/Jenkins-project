pipeline {
  agent {
    docker { image 'ngnix-latest' }
  }
  stages {
    stage('Test') {
      steps {
        sh 'node --version'
      }
    }
  }
}
