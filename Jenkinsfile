pipeline {
    agent {
        label 'worker'
    }
    stages {
        stage('Building') {
            steps{
                sh 'build.sh'
            }
        }
    }
}