pipeline {

agent any

    stages {
        stage('Example Build') {
            steps {
                ansiColor('xterm') {
                 ansiblePlaybook(
                     playbook: './playbook.yml',
                     inventory: './inventory.ini',
                     colorized: true)
                }
            }
        }
    }
}