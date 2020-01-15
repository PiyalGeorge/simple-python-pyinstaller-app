pipeline {
    agent { docker { image 'python:3.5.1' } }
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
