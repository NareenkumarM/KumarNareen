pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {

                https://github.com/NareenkumarM/KumarNareen
                {
            
        }
        stage('Build') {
            steps {
                
                sh 'mvn clean package'
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
        stage('Deploy') {
            steps {
                sh 'java -jar target/simple-springboot-app.jar'
            }
        }
    }
}
