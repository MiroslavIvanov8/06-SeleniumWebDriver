pipeline {
    agent any
    stages {
        stage('Build project') {
            steps {
                bat 'dotnet build'
            }
        }
        stage('Execute audit') {
            steps {
                bat 'dotnet audit'
            }
        }
        stage('Execute tests') {
            steps {
                bat 'dotnet test'
            }
        }        
    }
}
