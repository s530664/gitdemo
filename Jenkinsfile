pipeline {
    agent any
        parallel (
    {
        build("task1")
    }
            )

    stages {
        stage('Build') {
            steps {
                echo 'Building..repo1'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..repo1'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....repo1'
            }
        }
    }
}
