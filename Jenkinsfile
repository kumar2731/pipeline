pipeline {
    agent any
    stages {
        stage('git') {
            steps {
                sh "git --version"
            }
        }
        stage('maven') {
            steps {
                sh "maven --version"
            }
        }
    }
}
