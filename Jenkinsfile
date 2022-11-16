pipeline {
    agent any
    tools { 
        maven 'maven3' 
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