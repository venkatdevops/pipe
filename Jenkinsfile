pipeline {
    agent any

    stages {
        stage ('Compile ') {

            steps {
                withMaven(maven : 'mvn') {
                    sh 'mvn compile'
                }
            }
        }

        stage ('oackage') {

            steps {
                withMaven(maven : 'mvn') {
                    sh 'mvn package'
                }
            }
        }


        
    }
}
