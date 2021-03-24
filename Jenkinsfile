pipeline {
    agent any 
    stages {
        stage('Clone') {
            steps {
                echo 'Cloning files ...'
                checkout scm 
            }
        }
        stage('Read') {
            steps {
                echo 'Read the file ...'
                readFile 'README.md'
            }
        }
    }
}
