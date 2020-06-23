pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                bash 'node --version'
                bash 'svn --version'
            }
        }
    }
}
