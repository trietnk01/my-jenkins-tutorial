pipeline {
    agent any
    stages{        
        stage('SSH server'){
            steps{
                sshagent(['ssh-remote']) {
                    sh 'ssh -o StrictHostKeyChecking=no -l root 14.225.219.196 touch test.txt'
                }
            }
        }
       
    }    
}
