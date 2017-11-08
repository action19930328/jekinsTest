pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "Hello World"'
        sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
		   '''
        sh 'a = 5'
      }
    }
    stage('error') {
      steps {
        sh 'echo $a'
      }
    }
  }
}