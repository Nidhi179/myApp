node{
  stage('SCM Checkout'){
    
    git 'https://github.com/Nidhi179/myApp.git'    
  }
  stage('Compile-Package'){
    def mvn_home = tool name: 'MAVEN3', type: 'maven'
    sh '${mvn_home}/bin/mvn pacakage'
  }
}
