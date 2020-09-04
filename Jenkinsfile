pipeline {
    agent any
    tools {nodejs "Node14"}
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
         stage('Config') {
            steps {
                sh 'npm config ls'
            }
        }
    }
}
