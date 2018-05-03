pipeline {

    agent any

        stages {
            stage('Example Build') {
                steps {
                    ansiColor('xterm') {
                     ansiblePlaybook(
                         colorized: true)
                    }
                }
            }
        }
}