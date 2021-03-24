pipeline {
    agent any 
    stages {
        stage('Clone') {
            steps {
                echo 'Making build directory'
                sh 'mkdir -p build'

                echo 'Cloning files ...'
                checkout scm 
            }
        }
        stage('Read') {
            steps {
                readFile 'build/README.md'
            }
        }
    }
}
