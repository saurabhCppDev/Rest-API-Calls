pipeline {
  agent any
  stages {
    stage ('version') {
      steps {
        echo 'mvn --version.'
      }
    }
	stage ('compile') {
      steps {
        bat 'mvn compile'
      }
    }

	stage ('test') {
      steps {
        bat 'mvn test'
      }
    }

	stage ('package') {
      steps {
        bat 'mvn package'
      }
    }

  }
}