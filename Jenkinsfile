pipeline {
    agent any
    tools {nodejs "testNode"}
    stages {
        stage('Build') { 
            steps {
                tool name: 'testNode'
                sh 'npm config ls' 
            }
        }
    }
}
