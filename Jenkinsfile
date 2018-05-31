pipeline {
  agent {
    label 'jdk9'
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