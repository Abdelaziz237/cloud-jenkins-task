pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/your-username/my-jenkins-project.git'
            }
        }
        stage('Execute Script') {
            steps {
                sh './list_files.sh'
            }
        }
    }
}
