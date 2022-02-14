pipeline {
    agent any
    stages {
        stage('Clone the Repo') {
            steps {
                sh 'echo Hello Jenkins'
            }
        }
        stage('Run the App') {
            steps {
                sh 'node JenkinsTestProject/app.js'
            }
        }
    }
}
