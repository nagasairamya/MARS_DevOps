pipeline{
agent any
     tools { 
        maven 'Maven 3.6.0'
     }       
         
    stages {
    stage ('SCM Checkout')
    {
        steps {
            git 'https://github.com/nagasairamya/MARS_DevOps.git/'
        }
    }
        stage ('clean')
        {
            steps {
               sh 'maven clean'
            }
        }
      }
  }
