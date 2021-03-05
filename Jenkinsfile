pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                withMaven(maven: 'maven-latest') {
                    sh 'mvn clean compile'
                }
            }
        }
    }
}
