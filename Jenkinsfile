pipeline {
    agent any
    triggers {
        pollSCM('*/5 * * * *')
    }
    stages {
        stage('git init') {
            steps {
                git 'https://github.com/bhanuprakash678910/mavenproj.git'
            }
        }
    }
}
