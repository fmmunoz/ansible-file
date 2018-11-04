pipeline {
  agent any
  stages {
    stage('IMPORT-GIT') {
      steps {
        git(url: 'https://github.com/fmmunoz/ansible-file.git', branch: 'master', changelog: true)
      }
    }
  }
}