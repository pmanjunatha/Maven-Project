pipeline {
    agent any
    stages {
        stage ('Initialize') {
            steps {
                sh '''
                    echo "PATH = C:/Program Files/Java/jdk1.8.0_181"
                    echo "M2_HOME = D:/Installed Softwares/apache-maven-3.5.4-bin/apache-maven-3.5.4"
                '''
            }
        }

        stage ('Build') {
            steps {
                sh 'mvn install' 
            }
        }
    }
}
