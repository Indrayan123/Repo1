pipeline {
  agent {
    node {
      label 'master'
    }
    
  }
  stages {
    stage('PreBuild') {
      steps {
        parallel(
          "PreBuild": {
            echo 'JAVA_App PreBuild Validation'
            
          },
          "Code Compile": {
            echo 'echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}'
            
          }
        )
      }
    }
  }
}