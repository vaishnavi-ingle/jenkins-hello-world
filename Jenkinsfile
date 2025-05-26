pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/vaishnavi-ingle/jenkins-hello-world.git'
            }
        }

        stage('Run Python Script') {
            steps {
                echo 'Running Python script...'
                bat 'python hello.py'
            }
        }
    }
}
