pipeline{
    agent any
    stages{
     stage ('build & test'){
            steps{
               sh  '''
                #!/bin/bash
                "phing package"
                '''
               
            }
        }
        }
}
