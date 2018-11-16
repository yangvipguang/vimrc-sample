pipeline {
  agent {
    docker {
      image 'maven:3'
      args '''-p 3000:3000
-v  /root/.m2:/root/.m2'''
    }

  }
  stages {
    stage('build') {
      steps {
        mail(subject: 'Test', body: 'Test', to: 'yangvipguang@126.com')
      }
    }
  }
}