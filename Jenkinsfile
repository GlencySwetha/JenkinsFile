pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo 'Hello World!'

            }
        }
        stage('Test') {
            steps {
                echo 'Tested!' 
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deployed!' 
            }
        }
    }
        post{
            always{
                echo 'Success or Failure'
            }
            success{
                echo 'Success'
            }
            failure{
                echo 'Failure'
            }
        }
    node {
    
    ansiColor('xterm') {
        
        stage "\u001B[31mI'm Red\u001B[0m Now not"
    }
}
   
}
