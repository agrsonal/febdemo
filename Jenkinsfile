    
node {
  stage('SCM Checkout') {
  git 'https://github.com/agrsonal/febdemo' 
  }
  stage('Build Package') {
 // Trigger and build downstream job Dmofreestyle, making changes
  echo 'Downstream job starting..'    
  build job: 'Dmofreestyle'
  }
 }
