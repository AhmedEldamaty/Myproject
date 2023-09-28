pipeline {
  agent {
    docker {
      image 'alpine'
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