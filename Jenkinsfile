pipeline {
    agent any
    tools {
        maven 'M3'
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package'
                
                // This runs the exact Linux command requested by your lab
                sh 'sleep 1000' 
            }
        }
    }
}
