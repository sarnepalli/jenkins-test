
pipeline {
    agent any
    triggers {
      githubPush()
    }
    stages {
        stage('Source') {
            steps {
	    git 'http://github.com/sarnepalli/jenkins-test'
		}
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
