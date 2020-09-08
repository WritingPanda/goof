pipeline {
  agent any

  stage('Build') {
    steps {
      sh npm install
    }
  }
  stage('Test') {
    steps {
      echo 'Testing...'
    }
  }
  stage('Deploy') {
    steps {
      echo 'Deploying...'
    }
  }
}
