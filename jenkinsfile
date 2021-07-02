pipeline {
  agent any
  stage ('Build') {
    stages {
      sh 'echo "HELLO WORLD"'
      sh '''
        echo "This will list current dir content"
        ls -lh
        '''
    }
  }
} 
