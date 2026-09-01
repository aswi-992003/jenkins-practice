pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build started'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing started'
            }
        }
      stage('Build') {
            steps {
              sh 'python3 app .py'
               }
            }

        stage('Deploy') {
            steps {
                echo 'Deployment started'
            }
        }
    }
}
