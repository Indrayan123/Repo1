pipeline {
  agent {
    node {
      label 'master'
    }
    
  }
  stages {
    stage('PreBuild') {
      steps {
        echo 'JAVA_App PreBuild Validation'
      }
    }
    stage('Initiate') {
      steps {
        echo 'Running %{env.BUILD_ID}'
      }
    }
  }
}