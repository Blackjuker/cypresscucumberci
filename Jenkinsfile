pipeline{
    agent{
        docker{
            image 'cypress/browsers'
            args '--entrypoint=""'
        }
    }
    stages{
        stage("test nvm"){
            steps{
                sh "npm --version"
            }
        }
    }
}