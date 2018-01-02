pipeline {
    agent { docker 'node:testNode' }
    stages {
        stage('Build') { 
            steps {
                sh 'npm --version' 
            }
        }
    }
}
