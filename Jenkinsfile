pipeline {
  agent {
    node {
      label 'kubenetes'
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