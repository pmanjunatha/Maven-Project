pipeline {
    agent any
    stages {
        stage ('Initialize') {
            steps {
              
                    echo "Intialising............."
            }
        }

        stage ('Build') {
            steps {
                sh "mvn clean install" 
            }
        }
    }
}
