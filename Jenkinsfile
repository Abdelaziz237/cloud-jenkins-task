pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git credentialsId: '5eaab4d0-d73c-4e5a-9f16-8aa94e81e564', url: 'https://github.com/your-username/my-jenkins-project.git'
            }
        }
        stage('Execute Script') {
            steps {
                sh './list_files.sh'
            }
        }
    }
}
