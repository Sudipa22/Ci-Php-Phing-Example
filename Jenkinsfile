pipeline{
    agent any
    stages{
     stage ('build & test'){
            steps{
               
                    bash "phing install-dependencies"
                    bash "phing package"
               
            }
        }
        }
}
