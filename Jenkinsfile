pipeline {
    agent { docker { image 'node:8', 'jenkins-docker' } }
    stages {
        stage('build') {
            steps {
                sh 'npm install'
            }
        }
    }
}
