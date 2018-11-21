pipeline{
agent any
  
  stages {
    stage ('SCM Checkout')
    {
      git 'https://github.com/nagasairamya/MARS_DevOps.git/'
    }
    stage ('compile stage')
  {
    sh 'mvn clean compile'
    }
  }
  }
