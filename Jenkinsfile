node
{
stage ('SCM Checkout')
{
git 'https://github.com/nagasairamya/MARS_DevOps.git'
}
stage ('compile-package')
{
  def mvnhome = tool name: 'Maven', type: 'maven'
  sh '$(mvnhome package)/bin/mvn package'
}
}

