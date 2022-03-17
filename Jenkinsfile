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
                bat 'npm run ng build'
            }
        }
    }
}
