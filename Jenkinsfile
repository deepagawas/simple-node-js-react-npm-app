pipeline {
    agent any
    tools {nodejs "9.3.0"}
    stages {
        stage('Build') { 
            steps {
                tool name: 'testNode'
                sh 'npm config ls' 
            }
        }
    }
}
