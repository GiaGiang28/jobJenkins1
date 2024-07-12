pipeline {
    agent any
    stages{
        stage('Clone') {
        steps {
            git branch: 'main', credentialsId: 'admin', url: 'https://github.com/GiaGiang28/jobJenkins1.git'
        }
        // stage('Push Docker hub') {
        //     steps {
        //         // This step should not normally be used in your script. Consult the inline help for details.
        //         withDockerRegistry(credentialsId: 'creden-dockerhub', url: '') {
        //             // some block 1111111111 222222  1111 22211111111111
        //             sh label: '', script: 'docker build -t giagiang28/jenkins:latest .'
        //             sh label: '', script: 'docker push giagiang28/jenkins'
        //         }
        //     }
        // }
    }
    }
}