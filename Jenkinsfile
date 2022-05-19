  pipeline {
    agent {
      node {
        label "master"
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
