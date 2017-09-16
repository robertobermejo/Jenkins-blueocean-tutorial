pipeline {
  agent {
    docker {
      image 'alpine:3.6'
    }
    
  }
  stages {
    stage('Initialize') {
      steps {
        echo 'This is a message on the pipeline and updated on github'
        echo 'Added another message from github'
      }
    }
  }
}