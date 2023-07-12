pipeline {
    // agent any --> On which slave we wanna run this job 
    agent any
    
    // stages --> how many stages you wanna have in this pipeline 
    stages{
        stage("start") {
            steps{
                echo "Starting to clone the given repository"
            }
        }
        
        stage("git-clone") {
            steps {
                git branch: 'feature-jenkins-pipeline', url: 'https://github.com/anshkush92college/jenkins-tutorial.git'
            }
        }
        
        stage("testing-repo") {
            steps {
                echo 'Testing the repository for tests'
            }
        }
        
        stage("build-repo") {
            steps {
                echo "Going to build the repository"
            }
        }
        
        stage("deploy-repo") {
            steps {
                echo "Going to deploy the repository"
            }
        }

        stage("end") {
            steps{
                echo "Ending the pipeline - Jenkinsfile in the github repo"
            }
        }
    }
}
