pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
		./build.sh
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
