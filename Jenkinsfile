pipeline {
     agent any
   stages {
       stage ('checkout') {
           steps {
               echo 'cloning the repo in to local server'
          }
       }
       stage ('build') {
           steps {
               echo 'build the code'
          }
       }
       stage ('test') {
           steps {
               echo 'test the code'
         }
       }
       stage ('depioy') {
           steps {
             echo 'deploy the code'
         }
       }
     }
   }
