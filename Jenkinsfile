pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh 'echo "ok"'
        git(url: 'https://github.com/3108Takahashi/test.git', branch: 'dev')
      }
    }

  }
}