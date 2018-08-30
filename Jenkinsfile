
node{
  stage('SCM Checkout'){
    git 'https://github.com/ranajai/my-repo'
    }
  stage('Compile-Package'){
    def mvnHome = tool name: 'mvn', type: 'maven'  
    sh $"{mvnHome}/bin/mvn package"
    }
}
