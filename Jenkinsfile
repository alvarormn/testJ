pipeline {
    agent { docker { image 'node:4.2.6' } }
    stages {
        stage('build') {
        steps {
            sh 'node main.js'

            }
        }
    }
}
