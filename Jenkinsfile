pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/Bhavyajain0604/freestyle-job.git'
            }
        }
        stage('Compile Java Code') {
            steps {
                sh 'javac HelloWorld.java'
            }
        }
        stage('Run Java Program') {
            steps {
                sh 'java HelloWorld'
            }
        }
    }
}
