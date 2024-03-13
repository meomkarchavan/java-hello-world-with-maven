pipeline {
    agent any
    tools {
        maven 'maven'
        jdk 'jdk-21'
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}