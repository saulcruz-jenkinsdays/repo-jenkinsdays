pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hola Mundo'
        sh 'java -version'
      }
    }
  }
}