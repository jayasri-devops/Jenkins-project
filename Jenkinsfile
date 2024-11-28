pipeline {
  agent {
    docker { image 'ngnix' }
  }
  stages {
    stage('Test') {
      steps {
        sh 'node --version'
      }
    }
  }
}
