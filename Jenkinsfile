pipeline {
  agent any
  stages {
    stage('') {
      steps {
        parallel(
          "Stage1": {
            sh 'echo "1"'
            
          },
          "Stage2": {
            sh 'echo "2"'
            
          }
        )
      }
    }
    stage('BEBE') {
      steps {
        sh 'wq'
      }
    }
  }
}