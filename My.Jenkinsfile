pipeline {
    agent any
    stages {
        stage('Checkout Source Code') {
            steps {
                checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/KirillAvdyeyev/java-maven-app.git']])
                sh 'ls -la' // You already have this, good
                sh 'pwd'   // Add this to see the current directory path
                sh 'ls -la .git' // Add this to confirm the .git directory exists
            }
        }
        stage("Build") {
            steps {
                echo 'Hello Building!'
            }
        }
        stage("Test") {
            steps {
                echo 'Hello Testing!'
            }
        }
        stage("Deploy") {
            steps {
                echo 'Hello Deploying!'
            }
        }
    }
}
