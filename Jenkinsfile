pipeline {
    agent any 
    
    stages {
        stage('build') {
            steps{
                // get some repo
                git 'https://github.com/AdminTurnedDevOps/go-webapp-sample.git'
            }
        }

        stage('teste') {
            steps{
                // echo some file
                sh 'go run main.go'
            }


        }
    }
}
