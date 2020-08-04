node{
  stage('SCM Checkout')
  {
  
  }
  stage('Compile-Package')
  {
  def mvnHome= tool nanme: 'maven', type:'maven'
  sh "${mvnHome}/bin/mvn package"
  }
}
