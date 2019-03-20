node {
  stage('SCM Checkout') {
  git 'https://github.com/agrsonal/febdemo'
  }
  stage('Build Package') {
  sh 'mvn package'
  }
 }
