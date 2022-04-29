pipeline {
    agent any
    stages {
        stage('Build'){
            steps{
                echo 'Building python files...'
                echo 'Build Complete'
                echo 'Output...'
                bat 'python sem.py'
            }
        }
    }
}