pipeline{
    agent any

    stages{
        stage('hello'){
          steps{
              sh'echo "hello world"'
          }
       }
         stage('gitCheckout'){
          steps{
            git branch: 'main', credentialsId: 'jenkins', url: 'git@github.com:Farooq244/jenkins.git'
                    }
          }
    }
}
