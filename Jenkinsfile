pipeline {
    agent any

    stages {

        stage('Install Dependencies') {
            steps {
                sh 'python3 -m pip3 install -r requirements.txt'
            }
        }

        stage('Run Application') {
            steps {
                sh 'python3 app.py'
            }
        }

        stage('Run Tests') {
            steps {
                sh 'pytest'
            }
        }
    }
}
