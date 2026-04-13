pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building application...'
            }
        }

        stage('Test') {
            steps {
               sh 'python3 test_app.py'
            }
        }
        
        stage('Run') {
            steps {
                sh 'python3 app.py'
            }
        }
    }
}
