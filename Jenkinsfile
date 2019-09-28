pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World mates"'
                sh '''
                    echo "Multiline shell steps works too well my son"
                    ls -lah
                '''
            }
        }
    }
}
