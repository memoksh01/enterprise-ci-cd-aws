pipeline {
  agent any

  stages {
    stage('Checkout') {
      steps {
        git 'https://github.com/memoksh01/enterprise-ci-cd-aws.git'
      }
    }

    stage('Quality Check') {
      steps {
        sh 'echo Running Quality Gate'
      }
    }

    stage('Build') {
      steps {
        sh 'echo Build Successful'
      }
    }

    stage('Deploy') {
      steps {
        sh 'echo Deployed to AWS'
      }
    }
  }
}