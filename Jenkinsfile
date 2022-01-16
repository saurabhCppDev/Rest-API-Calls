pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                sh 'mvn --version'
            }
        stage('build') {
            steps {
                sh 'mvn compile'
            }
        stage('test') {
            steps {
                sh 'mvn test'
            }
        stage('package') {
            steps {
                sh 'mvn package'
            }
        }
    }
}