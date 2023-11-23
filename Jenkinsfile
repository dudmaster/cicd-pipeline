pipeline {
    agent any
    stages {
        stage('Started ansible playbook') {
            steps {            
                ansiblePlaybook credentialsId: 'github-ssh-key', disableHostKeyChecking: true, installation: 'Ansible', inventory: '/etc/ansible/hosts', playbook: '/etc/ansible/docker-install.yml', vaultTmpPath: ''
            }
        }
    }
}
