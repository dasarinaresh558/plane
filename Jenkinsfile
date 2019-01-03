pipeline { 
    agent any 
    stages {
        stage('clone') { 
            steps {
                bat 'mvn clean -f plane'
            }
        }
        stage('Test'){
            steps {
                bat 'mvn test -f plane ' 
            }
        }
        stage('Deploy') {
            steps {
                bat 'mvn deploy -f plane' 
