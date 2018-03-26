pipeline {
  agent any
  stages {
    stage('pull') {
      steps {
        git(url: 'https://github.com/tomcangbk/flask-jenkins-sample.git', branch: 'master')
      }
    }
  }
}