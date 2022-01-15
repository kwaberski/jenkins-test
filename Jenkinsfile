pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Running build automation'
            }
        }
        stage('DeployToStaging') {
            when {
                branch 'master'
            }
            steps {
                echo 'Deploying to Staging'
            }          
        }
    }
}
