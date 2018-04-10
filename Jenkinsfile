pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
  stages {
    stage('Run') {
      steps {
        sh 'mvn -v'
      }
    }
  }
}
