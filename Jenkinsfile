pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
      sh 'echo "HELLO WORLD"'
      sh '''
        echo "This was will list current dir content"
        ls -lh
        '''
      }
    }
  }
} 
