pipeline {
  agent {
    docker {
      image 'alpine:latest'
    }

  }
  stages {
    stage('test') {
      agent any
      steps {
        sh 'echo "test" '
      }
    }

  }
}