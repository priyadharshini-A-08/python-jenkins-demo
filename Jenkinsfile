pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git "githttps://github.com/priyadharshini-A-08/python-jenkins-demo.git"

            }
        }

        stage('Build') {
            steps {
                sh '''
                python_file hello.py
                '''
            }
        }
    }
}
