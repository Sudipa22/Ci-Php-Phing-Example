pipeline{
    agent any
    tool name: 'phing', type: 'hudson.plugins.phing.PhingInstallation'
    stages{
     stage ('build & test'){
            steps{
               
                    sh "phing install dependencies"
               
            }
        }
        }
}
