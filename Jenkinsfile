pipeline{
    agent any
    stages{
        stage('Dependency check'){
            steps{
                echo 'checking the vulnerability'
            }
        }
        stage('Code Build'){
            steps{
                echo 'Jenkins is Building'
            }
        }
        stage('Sonar scan'){
            steps{
                echo 'Sonar analysis'
            }
        }
        stage('Build and push'){
            steps{
                echo 'Building and pushing image to Jfrog'
            }
        }
        stage('Deployment to K8s'){
            steps{
                echo 'Deploying the image to K8s cluster'
            }
            
        }
    }
}

