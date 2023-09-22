@Library('shared_lib') _
pipeline {
    agent any

    stages {
        stage('Install Nginx') {
            steps {
                installNginx()
            }
        }
    }
}
