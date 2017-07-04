pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Done'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Done'
      }
    }
    stage('Test') {
      steps {
        parallel(
          "Test": {
            echo 'Done Testing'
            
          },
          "Browser Tests": {
            echo 'Done Browser tests'
            
          }
        )
      }
    }
    stage('Production') {
      steps {
        echo 'Up and running'
      }
    }
  }
}