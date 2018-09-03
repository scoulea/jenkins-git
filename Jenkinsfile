pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Andrew says Hello World,  but need jenkins to pick this up."'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
