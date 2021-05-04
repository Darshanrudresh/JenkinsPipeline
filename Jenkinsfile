node{
  stage('SCM Checkout'){
    git 'https://github.com/Darshanrudresh/JenkinsPipeline'
  }
  stage ('Complie-Package'){
    dwf MvnHome = tool name: '', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  } 
}
