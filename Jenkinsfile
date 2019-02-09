pipeline {
    agent any
    node {
        checkout([$class: 'GitSCM', branches: [[name: 'frstbranch']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/s530664/gitdemo.git']]])
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building..pavan'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..pavan'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....pavan'
            }
        }
    }
}
