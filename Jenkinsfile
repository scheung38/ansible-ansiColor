pipeline {

    agent any

        stages {
            stage('Example Build') {
                steps {
                    ansiColor('xterm') {
                     ansiblePlaybook(
                         playbook: ${WORKSPACE}/playbook.yml,
                         colorized: true)
                    }
                }
            }
        }
}