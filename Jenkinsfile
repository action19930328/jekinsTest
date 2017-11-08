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
      }
    }
    stage('') {
      steps {
        mail(subject: 'test', body: 'hello test', from: '997332992@qq.com', to: 'kaisheng.an@renren-inc.com')
      }
    }
  }
}