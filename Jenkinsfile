pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Andrew says Hello World,  but need jenkins to pick this up. Yawn finally changes?"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
