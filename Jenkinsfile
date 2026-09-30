
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building Docker project...'
            }
        }

        stage('Docker Build') {
            steps {
                bat 'docker build -t gopuvarshini14/jenkins-demo:v1 .'
            }
        }
    }
}
