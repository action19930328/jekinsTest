pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''echo "Hello World"
a = 5'''
        sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
		   '''
        sh 'a = 5'
      }
    }
    stage('') {
      steps {
        sh 'echo $a'
      }
    }
  }
}