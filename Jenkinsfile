pipeline {
    agent any
    tools {
        maven 'Maven1'
    }
    stages {
        stage('Build') {
            steps {
                echo 'ma ko te jebe'
                sh 'java --version'
                sh 'mvn clean compile'
            }
        }
    }
}