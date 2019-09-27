pipeline{
    agent any
    stages{
     stage ('build & test'){
            steps{
               sh  '''
                #!/bin/bash
              sh 'composer install'
                '''
               
            }
        }
        }
}
