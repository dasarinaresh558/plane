pipeline { 
    agent any 
    stages {
        stage('clone') { 
            steps {
                bat 'mvn clean'
            }
        }
        stage('Test'){
            steps {
                bat 'mvn test ' 
            }
        }
        stage('Deploy') {
            steps {
                bat 'mvn deploy' 
            }
        }
            }
        }
