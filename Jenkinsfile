pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Andrew says Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
