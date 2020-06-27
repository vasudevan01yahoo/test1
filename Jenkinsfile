node {
  try {
    stage('Checkout') {
      checkout scm
    }
    stage('Environment') {
      bat 'git --version'
      echo "Branch: ${env.BRANCH_NAME}"
     
     
    }
    stage('Build Docker test'){
      echo "dt"
    }
    stage('Docker test'){
      echo dt
    }
    stage('Clean Docker test'){
      echo "cdt"
    }
    stage('Deploy'){
     echo "deploy"
      }
    }
  }
  catch (err) {
    throw err
  }
}
