pipeline {
    agent {label 'xxx'}

    stages {
        stage('1. Hello1') {
            steps {
                sh 'touch sample.txt'
            }
        }
        
        stage('2. Git clone') {
            steps {
                git 'https://github.com/handuy/nodejs-todolist.git'
            }
        }
    }
}
