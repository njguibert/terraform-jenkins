  pipeline {
    agent {
      node {
        label "main"
      } 
    }

    stages {
      stage('TF Init&Plan') {
        steps {
          sh 'terraform --version'
        }      
      }
    } 
  }
