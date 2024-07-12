pipeline {
    agent any
    stages{
        stage('Clone') {
        steps {
            git branch: 'main', credentialsId: 'admin', url: 'https://github.com/GiaGiang28/jobJenkins1.git'
        }
    }
    }
}