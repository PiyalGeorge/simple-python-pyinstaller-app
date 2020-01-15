pipeline {
    agent { docker { image 'python:3.5-alpine' } }
    stages {
        stage('build') {
            steps {
                echo 'hello melcow'
                sh 'python --version'
                sh 'python justfun.py'
            }
        }
    }
}
