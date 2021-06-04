pipeline {
  agent any
  stages {
      stage('Parallel') {
       parallel {
        stage('compilation') {
          steps {
            echo 'Compiling'
          }
        }
        stage('test') {
          steps {
            echo 'testing'
          }
        }
        stage('Package') {
      steps {
        echo 'Packaging'
          }
        }
      }
    }
  }
}
