pipeline {

agent none

    stages {
        stage('Example Build') {
            steps {
                ansiColor('xterm') {
                 ansiblePlaybook(
                     playbook: '/Users/miriam-z/PycharmProjects/ansible-ansiColor/playbook.yml',
                     inventory: '/Users/miriam-z/PycharmProjects/ansible-ansiColor/inventory.ini',
                     colorized: true)
                }
            }
        }
    }
}