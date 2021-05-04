node{
  stage('SCM Checkout'){
    git 'https://github.com/Darshanrudresh/JenkinsPipeline'
  }
  stage ('Complie-Package'){
    def MvnHome = tool name: '', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  } 
}
