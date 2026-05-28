pipeline {
    agent any

    stages {

        stage('Install') {
            steps {
                bat 'npm install'
            }
        }

        stage('Run App') {
            steps {
                bat 'node app.js'
            }
        }

        stage('Test') {
            steps {
                bat 'npm test'
            }
        }

    }
}