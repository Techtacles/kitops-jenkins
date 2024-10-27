pipeline {
    agent any 
    stages {
        stage('install kitops') {
            steps {
                sh 'wget https://github.com/jozu-ai/kitops/releases/latest/download/kitops-linux-arm64.tar.gz'
                sh 'tar -xzvf kitops-linux-x86_64.tar.gz'
                sh './kit version'
            }
        }

        stage('Login to JozuHub'){
            steps {
                sh 'Logging in complete'
            }
        }
    }
}
