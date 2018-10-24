pipeline {
  agent any
  tools {
        maven 'localmaven'
        jdk 'jdk1.9'
    }
  stages {
    stage('Build') {
      steps {
          sh 'mvn compile'
      }
    
    }
    stage('Test') {
      steps {
          echo "Testing......!"
      }
    
    }
    stage('Package') {
      steps {
          echo "Packaging......!"
      }  
    }
  }
}
