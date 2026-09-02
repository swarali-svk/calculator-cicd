pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                sh 'docker build -t calculator .'
            }
        }
        stage('Test'){
            steps{
                sh 'docker run calculator'
            }
        }
    }
}