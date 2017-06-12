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
    stage('set Maven Path') {
      steps {
        bat 'set PATH=%PATH%;C:\\JDEV12R2V1SOA\\oracle_common\\modules\\org.apache.maven_3.2.5\\bin'
      }
    }
  }
}