pipeline {
     agent any
    stage ('Depoly'){
        steps{
    sshagent (credentials: ['sshkey']) {
        sh 'ssh -o StrictHostKeyChecking=no gowri@107.180.89.242 uname -a'
        }
   }
    }
    }

