pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
				.gradlew clean build
				echo 'Building..done'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
