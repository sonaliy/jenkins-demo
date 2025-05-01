pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
       stage('Dev') {
            steps {
                git 'https://github.com/sonaliy/jenkins-demo.git'
                echo 'content of my file is'
                sh 'cat README.md'
            }
        }
    }
}
