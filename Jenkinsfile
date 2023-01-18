pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                bat 'echo "Hello, World!"'
            }
        }
        stage('deploy') {
            steps {
                bat 'echo "Depolyed Successfully!"'
            }
        }
        stage('read') {
            steps {
                script {
                    def data = readFile(file: 'test.txt')
                    println(data)
                }
            }
        }
    }
}