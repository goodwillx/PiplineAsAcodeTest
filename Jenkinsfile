pipeline {
  agent any
  stages {
    stage('Bulid ') {
      steps {
        echo 'Build Completed'
        timeout(time: 5, unit: 'SECONDS') {
          sh 'sleep 9'
       }
      }
    }

    stage('Test ') {
      steps {
        echo 'Testing Completed'
      }
    }

  }
}
