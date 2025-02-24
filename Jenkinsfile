pipeline {
    agent any
    tools {
  maven 'maven3'
    }

    stages {
        stage('CHECKOUT') {
            steps {
                echo 'Its configured from jenkins UI'
            }
        }
        stage('maven build') {
            steps {
                sh "mvn clean package"
            }
        }
    }
}
