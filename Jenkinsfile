pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
			bat 'echo "in jenkinsfile"'
                bat 'mvn build clean'
            }
        }
    }
}