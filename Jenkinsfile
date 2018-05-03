pipeline {

    agent any

        stages {
            stage('Example Build') {
                steps {
                    ansiColor('xterm') {
                     ansiblePlaybook(
                         playbook: "${ANSIBLE_DATA_PATH}/playbooks/playbook.yml",
                         colorized: true)
                    }
                }
            }
        }
}