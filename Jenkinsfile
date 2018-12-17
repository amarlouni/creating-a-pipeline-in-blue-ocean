pipeline {
  agent {
    docker {
      image 'node:6-alpineet'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }
  }
}