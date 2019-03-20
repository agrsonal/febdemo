node {
  stage('SCM Checkout') {
  git 'https://github.com/agrsonal/febdemo'
  }
  stage('Build Package') {
    def mvnHome = tool name: 'mymaven', type: 'maven'
    sh "S{mvnHome}/bin/mvn package"
  }
 }
