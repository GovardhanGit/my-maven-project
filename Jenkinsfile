pipeline {
    agent any 
    stages {
        stage('----clone-----') { 
            steps {
                
                sh "mvn clean"
            }
        }
        stage('-----Test----') { 
            steps {
                sh "mvn test" 
            }
        }
        stage('---package-----') { 
            steps {
                sh "mvn package" 
            }
        }
    }
}
