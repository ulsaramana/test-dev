pipeline {
  agent any

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
