pipeline {
    agent any
    stages {
        stage('Compile') {
            steps { 
                sh 'mvnn compile'
            }
        }
        stage('test') {
            steps { 
                sh 'mvn test'
            }
        }
        stage('package') {
            steps { 
                sh 'mvn package'
            }
        }
    }
}
