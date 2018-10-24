pipeline {
    agent any
    
    stages {
        stage('build') {
            steps {
                echo "Building a maven project........!"
                sh 'mvn compile'
            }
        }
        stage('test') {
            steps {
                echo "Testing........!"
                sh 'mvn test'
            }
        }
        
    }
}
