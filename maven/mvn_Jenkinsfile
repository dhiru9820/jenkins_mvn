pipeline {
    
    agent any

    tools {
        maven 'maven-3.6.3'
    }

    stages {
        stage ('Check-Maven') {
            steps {
                sh 'mvn -version'
            }
        }

        stage ('Clean Maven Package') {
            steps {
                sh 'mvn clean package'
            }
        }
    }



}