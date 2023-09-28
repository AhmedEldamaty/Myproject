pipeline {
  agent {
    node {
      label 'ubuntu'
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