pipeline{
agent any
    stages {
    stage ('SCM Checkout')
    {
        steps {
            git 'https://github.com/nagasairamya/MARS_DevOps.git/'
        }
    }
        stage ('Build')
        {
            steps {
                echo " This is a minimal pipeline"
                sh 'mvn -B -DskipTests clean package'
            }
        }
      }
  }
