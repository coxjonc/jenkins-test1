pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
                sh 'echo "Hello world"'
                sh '''
                echo "Multiline works wow"
                ls -lrt
                '''
            }
        }
    }
}
