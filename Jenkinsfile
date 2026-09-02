pipeline {
    agent any

    stages {

        stage('Checkout Code') {
            steps {
                git branch: 'main', url: 'https://github.com/Sarath-venkat/CalculatorPipeline.git'
            }
        }

        stage('Build') {
            steps {
                bat 'python sum.py'
            }
        }
    }
}