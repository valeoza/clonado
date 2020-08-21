
pipeline {
    agent any
    stages {
        stage('Compile') {
            steps {
                gradlew('clean', 'classes')
            }
        }
        stage('Assemble') {
            steps {
                gradlew('assemble')
            }
        }
    }
}
