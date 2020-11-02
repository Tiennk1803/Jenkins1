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
                git 'https://github.com/Tiennk1803/Jenkins1.git'
            }
        }

        stage('3. Echo') {
            steps {
                echo 'Clone git done'
            }
        }
    }
}
