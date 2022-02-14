pipeline {
    agent any

    stages {
        stage('Clone the Repo') {
            steps {
                sh 'rm -rf JenkinsTestProject'
                sh 'git clone https://github.com/denukedissanayake/JenkinsTestProject.git'
            }
        }
        stage('Run the App') {
            steps {
                sh 'ls'
                sh 'cd JenkinsTestProject'
                sh 'ls'
                sh 'node JenkinsTestProject/app.js'
            }
        }
    }
}
