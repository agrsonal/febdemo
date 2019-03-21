pipeline {
  stages { 
  stage('SCM Checkout') {
  git 'https://github.com/agrsonal/febdemo'
  }
  triggers { 
  upstream(upstreamProjects: 'Dmofreestyle', threshold: hudson.model.Result.SUCCESS)
  }
  stage('Testing') {
    steps {
     echo 'Testing...'
    }
  } 
  }
 }
