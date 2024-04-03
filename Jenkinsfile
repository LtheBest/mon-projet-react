pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                echo 'Building the project...'
                sh 'npm install'
            }
        }
        stage('Test'){
            steps{
                echo 'Testing the project...'
                sh'npm test'
            }
        }
        stage('Deploy / Deliver '){
            steps{
                echo 'Deploying the project...'
            }
        }
    }
}