pipeline{
    agent any
    tools {
        phing 'phing' 
    }
    stages{
     stage ('build & test'){
            steps{
               
                    sh "phing install dependencies"
               
            }
        }
        }
}
