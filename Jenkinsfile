pipeline {
  agent any

  stages {
    stage('Checkout') {
      steps {
        git 'https://github.com/aarchi123-34/jenkins-demo.git'
      }
    }

    stage('Build') {
      steps {
        echo 'Building...'
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
}
