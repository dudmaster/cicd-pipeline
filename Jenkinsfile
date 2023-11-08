pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        sh 'ansible-playbook -i hosts playbook.yml'
      }
    }
  }
}
