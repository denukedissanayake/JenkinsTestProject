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
                sh 'ls'
                'node app.js'
            }
        }
    }
}
