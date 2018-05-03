pipeline {

    agent any

        stages {
            stage('Example Build') {
                steps {
                    ansiColor('xterm') {
                     ansiblePlaybook(
                         playbook: "ansible-ansiColor/playbooks/playbook.yml",
                         colorized: true)
                    }
                }
            }
        }
}