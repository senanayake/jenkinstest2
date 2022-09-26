pipeline {
    agent any

    stages {
        stage('git version') {
            steps {
               sh "git version"
            }
        }
        stage('maven version') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                sh "mvn -v"
            }
        }
    }
}
