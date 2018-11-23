pipeline{
agent any
     tools { 
        maven 'apache-maven-3.6.0'
     }       
         
    stages {
    stage ('SCM Checkout')
    {
        steps {
            git 'https://github.com/nagasairamya/MARS_DevOps.git/'
        }
    }
        stage ('compile')
        {
            steps {
                 withMaven(Maven : "apache-3.6.0-"){
               bat 'mvn clean install'
            }
            }
        }
      }
  }
