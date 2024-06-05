pipeline {    
    agent any 
    tools {
        jdk 'jdk17'
        maven 'maven3'
    }

    stages {   
        stage('Compilee') {
            steps {
                sh 'mvn compile'
            }
        }
        
        stage('Test') {
            steps {
                sh 'mvn tesst'
            }
        }
        
        stage('Build') {
            steps {
                sh 'mvn package'
            }
        }
    }
}
