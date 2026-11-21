pipeline {
    agent any
    stages {
        stage('Test calculator') {
            steps {
                sh 'python3 sources/test_calc.py'
                sh'ls'
                sh'ls -la'
                sh'pwd'
                sh'whoami'
                sh'hostname'
                echo 'hello world'
            }
        }
    }
}
