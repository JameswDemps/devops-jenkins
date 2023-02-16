pipeline {
    agent any
    stages {
        stage('Pipeline Stages'){
            steps {
                sh "mkdir ~/jenkins-tutorial-test1"
            }
        }
        stage('second stage'){
            steps {
                sh "touch ~/jenkings-tutorial-test1/file1 ~/jenkins-tutorial-test1/file2"
            }
        }
    }
}