pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                 sh 'mvn clean package'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing application'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application'
            }
        }
    }
}
echo 'Build process completed successfully'
echo '23MIS0117 Sivashree'
