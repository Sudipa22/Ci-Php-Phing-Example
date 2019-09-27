pipeline{
    agent any
    stages{
     stage ('build & test'){
            steps{
               sh  '''
                #!/bin/bash
              sh 'phing install-dependencies'
                '''
               
            }
        }
        }
}
