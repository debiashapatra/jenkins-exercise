pipeline {
    agent any
    environment{
    Version='1.3'
    }
    stages{
        stage("Build"){
            steps{
                echo "Building the application"
                echo "version is ${Version}"
            } 
        }
        stage("Test"){
            steps{
                echo "Testing the application"
            }
        }
        stage("Deploy"){
            steps{
                echo "deploying the application"
            }
        }
    }

}
