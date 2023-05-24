pipeline {
    agent any
    stages{
        stage('ssh'){
    sshagent (credentials: ['sshkey']) {
        sh 'ssh -o StrictHostKeyChecking=no gowri@107.180.89.242 uname -a'
        }
   }
    }
    }

