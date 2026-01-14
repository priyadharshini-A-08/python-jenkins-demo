pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                bat '"C:\\Users\\Personal\\AppData\\Local\\Programs\\Python\\Python314\\python.exe" demo.py'
                
            }
        }
    }
}
