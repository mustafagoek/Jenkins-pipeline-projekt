pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "this is example pipeline project"
                sh 'echo using shell within Jenkinsfile'
                echo 'not using shell in the Jenkinsfile'
            }
        }
        stage('test') {
            steps {
                echo "this is example pipeline project and test it"
                sh 'echo using shell within Jenkinsfile'
                echo 'not using shell in the Jenkinsfile'
            }
        }
    }
}
