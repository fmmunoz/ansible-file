pipeline {
  agent any
  stages {
    stage('EXEC-PLAYBOOK') {
      steps {
        ansiblePlaybook(playbook: 'prueba.yml', colorized: true, disableHostKeyChecking: true, dynamicInventory: true, inventoryContent: '192.168.1.41')
      }
    }
  }
}