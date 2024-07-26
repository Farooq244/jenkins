pipeline{
    agent any

    stages{
        stage('gitCheckout')
          steps{
            git branch: 'main', credentialsId: 'jenkins-git', url: 'git@github.com:Farooq244/jenkins.git'
          }
    }
}