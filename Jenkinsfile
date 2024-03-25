pipeline {
    agent any
    tools {
        maven 'maven'
   }
    stages {
        stage('validate') {
            steps {
                sh 'mvn validate'
            }
        }
            stage('compile') {
            steps {
                sh 'mvn compile'
            }
        }
            stage('test') {
            steps {
                sh 'mvn compile'
            }
        }
            stage('package') {
            steps {
                sh 'mvn compile'
            }
        }
            stage('verify') {
            steps {
                sh 'mvn compile'
            }
        }
        
    }
}
