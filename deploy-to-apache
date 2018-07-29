node{
  stage('Git Checkout'){
      git url: 'https://github.com/javahometech/my-app',
          branch:'master'
  }
  stage('Build Docker Image'){
    sh 'docker build -t awsdevopro/phphelloworld:0.0.1 .'
  }
}
