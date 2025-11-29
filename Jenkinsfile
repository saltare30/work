pipeline {
    agent any
    stages {
        stage('Run Python Script') {
            steps {
                sh 'python3 main.py'
            }
        }
        stage('Python version') {
            steps {
                sh 'python3 -v'
            }
        }

    }
}