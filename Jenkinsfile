pipeline {
  agent {
    docker {
      image 'node:6-alpine'
      args '-p 3000:3000'
      label 'mx-jnlp'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'npm install'
      }
    }
  }
}
