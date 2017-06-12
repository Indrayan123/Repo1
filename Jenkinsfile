pipeline {
  agent {
    node {
      label 'master'
    }
    
  }
  stages {
    stage('Initiate') {
      steps {
        echo 'Running %env.BUILD_ID'
      }
    }
  }
}