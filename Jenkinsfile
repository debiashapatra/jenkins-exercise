pipeline {
    agent any
    environment{
    Version='1.3'
    server_cred=credential('server-credential')
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
                echo "deploying in ${server_cred}"
            }
        }
    }

}
