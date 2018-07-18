pipeline {
  agent {
    dockerfile {
      filename 'alpine'
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