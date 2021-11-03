node{
  stage('SCM Checkout'){
    git 'https://github.com/olusesa/my-app'
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
}
