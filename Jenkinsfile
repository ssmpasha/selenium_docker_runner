pipeline{
    agent any

    stages{
        stage('Start Test'){
            steps{
                bat "docker-compose up"
            }
        }
        stage('Stop Test'){
            steps{
                bat "docker-compose down"
            }
         }
    }
}