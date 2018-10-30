pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
				echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
				echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
				echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
    }
}
