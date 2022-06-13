pipeline {
    agent {
        label 'worker'
    }
    stages {
        step('Building') {
            sh 'build.sh'
        }
    }
}