pipeline {
    agent any

    stages {
        stage('DownloadDependencies'){
            steps{
                bat 'npm install'
            }
        }
        stage('build'){
            steps{
                echo 'npm run ng build'
            }
        }
    }
}
