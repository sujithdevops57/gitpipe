pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/sujithdevops57/pipelines-prac.git', branch: 'main'
            }
        }

        stage('Build') {
            steps {
                echo 'Building project...'
                sh 'echo Hello from Jenkins!'
            }
        }
    }
}
