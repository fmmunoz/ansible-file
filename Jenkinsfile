pipeline {
  agent any
  stages {
    stage('COMPRUEBA-GIT') {
      steps {
        git(url: 'https://github.com/fmmunoz/ansible-file.git', branch: 'master', changelog: true)
      }
    }
    stage('CLONE') {
      steps {
        sh 'cd /opt && git clone https://github.com/fmmunoz/ansible-file.git'
      }
    }
  }
}