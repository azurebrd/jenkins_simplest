pipeline {
    agent { docker { image 'node:6.3' } }
    stages {
        stage('build') {
            steps {
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
                sh 'npm --version'
            }
        }
    }
}
