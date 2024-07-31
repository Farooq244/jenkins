pipeline{
    agent {
        label 'slave1'
    }

    stages{
        stage('hello'){
          steps{
              sh'echo "hello world"'
          }
       }
         stage('gitCheckout'){
          steps{
            git branch: 'main', url: 'https://github.com/Farooq244/jenkins.git'
          }
          }
    }
}
