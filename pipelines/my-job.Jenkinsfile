pipeline {
    agent any
    stages {
        stage("change dir") {
            steps {
                dir ("/var/jenkins_home/") {
                    sh "pwd"
                }
            }
        }
        stage ("cat") {
            steps {
               sh "pwd"
            }
        }
    }