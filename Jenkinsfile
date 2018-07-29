node{
  stage('Git Checkout'){
      git url: 'https://github.com/awsdevopro/phphelloworld.git',
          branch:'master'
  }
  stage('Build Docker Image'){
    sh 'docker build -t awsdevopro/phphelloworld:0.0.1 .'
  }
}
