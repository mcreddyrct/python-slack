pipeline {
    agent any

    stages {
        stage('Checkout SCM') {
            steps {
                echo 'Code has been checked out in the GIT'
            }
        }
		stage('Build') {
            steps {
                echo 'War/Jar file created from the pom.xml file'
            }
        }
		stage('Deploy') {
            steps {
                echo 'War/Jar deployed to taget server '
            }
        }
		stage('Test') {
            steps {
                echo 'Santity check completed for the Hello world application'
            }
        }
    }
}