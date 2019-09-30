pipeline{
    agent any
    stages{
     stage ('build & test'){
            steps{
                sh "phing -version"
                sh "phing install-dependencies"
               jacoco()
               
            }
        }
        }
}
