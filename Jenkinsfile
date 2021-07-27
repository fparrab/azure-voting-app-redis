pipeline {
   agent any

   stages {
      stage('Verify Branch') {
         steps {
            echo "$GIT_BRANCH"
         }
      }
      
    stage('Setting the variables values') {
    steps {
         sh '''#!/bin/bash
                 echo "hello world" 
         '''
    }
}
   }
   
   
}
