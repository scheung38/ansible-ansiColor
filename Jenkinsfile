pipeline {

    agent any

        stages {
            stage('Example Build') {
                steps {
                    ansiColor('xterm') {
                     ansiblePlaybook(
                         playbook: '${WORKSPACE}/ansiColor/playbook.yml',
                         colorized: true)
                    }
                }
            }
        }
}