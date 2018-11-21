pipeline{
agent any
  
  stages {
    stage ('SCM checkout'){
    steps {
    git 'https://github.com/nagasairamya/MARS_DevOps.git'
  }
  }
  stage ('compile stage')
  {
    steps {
    withMaven(maven : 'Maven')
    {
      sh 'mvn clean compile'
    }
  }
  }
  stage ('testing stage'){
    steps {
      withMaven(maven : 'Maven'){
    sh 'mvn test'
  }
  }
  }
  
}
