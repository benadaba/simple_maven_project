pipeline {
    agent any
    tools { 
        maven 'maven 3.8.6' 
        jdk 'jdk8'
    }
    stages {
        stage('build') {
            steps {
                sh 'maven clean install'
            }
        }
    }
}