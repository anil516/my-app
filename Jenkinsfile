node{
  stage('SCM Checkout')
  {
   git 'https://github.com/anil516/my-app.git'
  }
  stage('Compile-Package')
  {
  def mvnHome= tool nanme: 'maven', type:'maven'
  sh "${mvnHome}/bin/mvn package"
  }
}
