pipeline {

    agent any

        stages {
            stage('Example Build') {
                steps {
                    ansiColor('xterm') {
                     ansiblePlaybook(
                         playbook: "${base}/playbooks/playbook.yml",
                         colorized: true)
                    }
                }
            }
        }
}