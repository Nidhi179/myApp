node{
  stage('SCM Checkout'){
    git 'https://github.com/Nidhi179/myApp.git'
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
}
