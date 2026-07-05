pipeline {
    agent any
    tools {
        maven 'Maven 3.3.9'
    }
    stages {
        stage('build-phase') {
            steps {
                bat 'mvn compile'
            }
        }
        stage('test-phase') {
            steps {
                bat 'mvn test'
            }
        }
        stage('package-phase') {
            steps {
                bat 'mvn package'
            }
        }
    }
}