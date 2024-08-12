pipeline {
    agent any
    tools {
        maven '3.8.1'
    }
    stages{
        stage('Build') {
            steps {
                echo "Building the code"
            }
        }
        stage('Test'){
            steps {
                echo "TEsting the code"
            }
        }
        stage('Deploy'){
            steps {
                echo "Deploying the code"
            }
        }
    }
}
