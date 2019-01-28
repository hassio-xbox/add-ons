pipeline {
    agent { docker { image 'node:8', label 'jenkins-docker' } }
    stages {
        stage('build') {
            steps {
                sh 'npm install'
            }
        }
    }
}
