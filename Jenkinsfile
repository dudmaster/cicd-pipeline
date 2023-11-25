pipeline {
    agent any
    stages {
        stage('Started ansible playbook') {
            steps {            
                ansiblePlaybook credentialsId: 'dudmaster', disableHostKeyChecking: true, installation: 'Ansible', inventory: '/etc/ansible/hosts', playbook: '/etc/ansible/docker-install.yml', vaultTmpPath: ''
            }
        }
    }
}
