pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/Ramprasad-1/Projectcicd.git'
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Building project..."'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "Deploying app..."'
            }
        }
    }
}
