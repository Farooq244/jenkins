pipeline{
    agent any

    stages{
        stage('gitCheckout')
          steps{
            git branch: 'main', credentialsId: 'jenkins-ssh', url: 'git@github.com:Farooq244/jenkins.git'          }
    }
}