
pipeline {
    agent any

    stages {
        stage('Source') {
	    git 'http://github.com/sarnepalli/jenkins-test'
        }
        stage('Test') {
            steps {
                echo 'Hello World..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Goodbye!'
            }
        }
    }
}
