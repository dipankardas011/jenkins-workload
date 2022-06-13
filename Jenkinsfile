pipeline {
    agent {
        label 'worker'
    }
    stages {

        stage ('git-checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/dipankardas011/jenkins-workload.git'
            }
        }

        stage('Building') {
            steps{
                sh 'chmod +x build.sh'
                sh './build.sh'
            }
        }
    }
}