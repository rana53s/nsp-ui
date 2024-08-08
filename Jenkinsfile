pipeline {
    agent any

    stages {
        stage("Clean Up") {
            steps {
                deleteDir()
            }
        }

        stage("Build") {
            steps {
                dir("nsp-web-page") {
                    sh "npm install"
                }
            }
        }
    }
}