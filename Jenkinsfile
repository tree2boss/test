pipeline {
  agent any
  stages {
    stage('first stage') {
      steps {
        echo 'this is first step'
      }
    }

  }
  post {
    always {
      echo 'this is ending...'
    }

  }
}