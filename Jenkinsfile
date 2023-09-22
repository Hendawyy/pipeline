@Library('shared_lib') _

pipeline {
    agent {
        label 'AWS'
    }

    stages {
        stage('Demo') {
            steps {
                script {
                    shared_lib.installnginx()
                }
            }
        }
    }
}
