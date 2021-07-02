pipeline {
  agent any
  
  stages {
    stage('Checkout') {
      steps {
        echo 'Checkout from git'
      }
    }
    
    stage('Install dependencies') {
      steps {
        echo 'Install pods'
      }
    }
    
    stage('Build') {
      steps {
        echo 'run xcode build'
      }
    }
    
    stage('Test') {
      steps {
        echo 'Run xcode tests'
      }
    }
    
    stage('Archive') {
      steps {
        echo 'Run xcode archive'
      }
    }
  }

}
