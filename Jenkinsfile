pipeline {
    agent { docker { image 'node:4.2.6' } }
    stages {
        stage('build') {
        steps {
            sh 'echo "Hello World"'
            sh '''
                echo "Multiline shell steps works too"
                ls -lah
            '''
        }
        }
    }
}
