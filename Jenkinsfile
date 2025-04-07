pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello from Jenkins Pipeline!'
            }
        }
        stage('Git Clone') {
            steps {
                git 'https://github.com/laszlo-nagy-a/jenkins-practice.git'
            }
        }
    }
}