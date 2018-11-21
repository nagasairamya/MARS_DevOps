pipeline{
agent any
    stages {
    stage ('SCM Checkout')
    {
        steps {
            git 'https://github.com/nagasairamya/MARS_DevOps.git/'
        }
    }
    stage ('compile stage')
  {
   steps
      {
          sh 'mvn clean install'
      }
    }
  }
  }
