pipeline {
    agent {
        label 'linux'
    }

    stages {
        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }

        stage('Unit Tests') {
            steps {
                echo 'Ejecutando unit tests'
            }
        }

        stage('Build') {
            steps {
                sh 'ng build'
            }
        }
    }
}
