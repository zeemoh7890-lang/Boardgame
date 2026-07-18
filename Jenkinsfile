pipeline {
    agent any
    
    tools {
        maven 'maven3'
        jdk 'jdk17'
    }
        
        stage('Compile') {
            steps {
                sh  'mvn compile'
            }
            }
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn package'
            }
        }
    }
