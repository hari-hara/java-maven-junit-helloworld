node{
  stage (' SCM Checkout'){
  git 'https://github.com/hari-hara/java-maven-junit-helloworld.git'
  }
  stage('Compile-Package'){
    def mvnHome = tool name: 'maven', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }	
 } 
