pipeline {

    agent any

        stages {
            stage('Example Build') {
                steps {
                    node {
                        ansiColor('xterm') {
                         ansiblePlaybook(
                             playbook: "playbook.yml",
                             colorized: true)
                        }
                    }

                }
            }
        }
}