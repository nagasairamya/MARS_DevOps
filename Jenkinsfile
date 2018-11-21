pipeline{
agent any
  
  stages {
    stage ('compile stage')
  {
    steps {
    withmaven(maven : 'Maven')
    {
      sh 'mvn clean compile'
    }
  }
  }
  }
}
