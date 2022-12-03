pipeline{
    agent any
    tools {
        jdk 'jdk8'
        maven 'maven3'   
    }

    stages {
        stage('Initialise') {
            steps {
            // One or more steps need to be included within the steps block.
            echo "PATH" = ${PATH}
            echo "M2_HOME = ${M2_HOME}"
            ls
            }
        }

        stage('Build') {
            steps {
            // One or more steps need to be included within the steps block.
             sh "mvn clean install"
            }
        }

}

}
