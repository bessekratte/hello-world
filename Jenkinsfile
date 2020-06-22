pipeline {
  agent {
    docker {
      image 'maven:3.3-jdk-8'
      args '-p 8080:8080'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'mvn -version'
      }
    }

  }
}