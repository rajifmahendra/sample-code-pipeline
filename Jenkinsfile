pipeline {
    agent any
    stages {
        stage('verify version') {
            steps {
                sh 'php --version'
            }
        }
        stage('Hello Rajif') {
            steps {
                sh 'pwd'
                sh 'php index.php'
            }
        }
    }
}
