pipeline {
  agent any
  tools {
        maven 'localmaven'
        jdk 'jdk1.9'
    }
  stages {
    stage('Build') {
      steps {
          sh 'mvn compile verify'
      }
    
    }
    stage('Test') {
      steps {
          echo "Testing......!"
      }
    
    }
    stage('cleanup') {
      steps {
          echo "Cleaning up the workspace"
          cleanWs()
      }  
    }
  }
}
