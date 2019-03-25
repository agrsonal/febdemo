    
node {
  stage('SCM Checkout') {
  git 'https://github.com/agrsonal/febdemo' 
  }
  stage('Build Package') {
 // Trigger and build downstream job Dmofreestyle
      build job: 'Dmofreestyle'
  }
 }
