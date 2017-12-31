pipeline {
  agent any
  stages {
    stage('StaticCode') {
      steps {
        git(url: 'https://github.com/sjeed/AntExample', branch: 'master')
      }
    }
  }
}
