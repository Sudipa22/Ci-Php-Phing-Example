pipeline{
    agent any
    stages{
     stage ('build & test'){
            steps{
                bash '''#!/bin/bash
               bash "phing install-dependencies"
                bash "phing package"
                '''
               
            }
        }
        }
}
