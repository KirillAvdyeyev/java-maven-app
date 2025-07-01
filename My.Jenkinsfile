pipeline {
    agent any
    stages {
        stage("Build") {
            steps {
                echo 'Hello Building! Time: ${new Date()}'
            }
        }
        stage("Test") {
            steps {
                echo 'Hello Testing! Time: ${new Date()}'
            }
        }
        stage("Deploy") {
            steps {
                echo 'Hello Deploying! Time: ${new Date()}'
            }
        }
    }
}
