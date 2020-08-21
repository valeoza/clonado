
pipeline {
    agent any
    stages {
        stage('Compile') {
            steps {
                sh 'gradlew clean'
               
            }
        }
        stage('Assemble') {
            steps {
                 sh 'gradlew assemble'
            }
        }
    }
}
