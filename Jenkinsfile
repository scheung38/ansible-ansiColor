pipeline {

    agent any

        stages {
            stage('Example Build') {
                steps {
                    ansiColor('xterm') {
                     ansiblePlaybook(
                         playbook: "/Users/miriam-z/.jenkins/workspace/ansiColor/playbook.yml",
                         colorized: true)
                    }
                }
            }
        }
}