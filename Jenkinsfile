pipeline {
    agent any
    tools {
        maven 'Apache-maven'
    }
    stages {
        stage ('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}