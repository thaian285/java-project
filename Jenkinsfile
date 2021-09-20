pipeline {
    agent any
    stages {
        stage("Build") {
            sh 'mvn DskipTests clean package'
        }
        stage("Test") {
            sh 'mvn test'
        }
    }
}
