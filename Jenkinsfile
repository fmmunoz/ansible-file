pipeline {
  agent any
  stages {
    stage('Ejecucion Playbook') {
      steps {
        ansiblePlaybook(playbook: '/opt/pruebaficheros/prueba.yml', colorized: true, disableHostKeyChecking: true, inventoryContent: '192.168.1.41')
      }
    }
  }
}