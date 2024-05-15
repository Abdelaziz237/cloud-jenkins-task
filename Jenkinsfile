pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', credentialsId: '5eaab4d0-d73c-4e5a-9f16-8aa94e81e564', url: 'https://github.com/Abdelaziz237/cloud-jenkins-task.git'
            }
        }
        stage('Execute Script') {
            steps {
                bat './list_files.bat'
            }
        }
    }
}
