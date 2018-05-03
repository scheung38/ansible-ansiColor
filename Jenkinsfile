pipeline {

    agent any

        stages {
            stage('Example Build') {
                steps {
                    ansiColor('xterm') {
                     ansiblePlaybook(
                         playbook: "playbooks/playbook.yml",
                         colorized: true)
                    }
                }
            }
        }
}