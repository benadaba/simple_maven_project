pipeline {
    agent any
    tools { 
        maven 'maven3' 
        jdk 'jdk8'
    }
    stages {
        stage('build') {
            steps {
                withMaven(maven: 'maven3')
                sh 'maven clean install'
            }
        }
    }
}