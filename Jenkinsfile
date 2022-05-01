pipeline {
  agent {
    node {
      label 'kubernetes'
    }

  }
  stages {
    stage('Test') {
      steps {
        sh 'kubectl get node'
      }
    }

  }
}