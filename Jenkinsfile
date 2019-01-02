pipeline {
    agent any
    stages {
        stage {
            stage('build'){
                steps {
                bat 'mvn clean package'
                }
            }
        }
    }
}