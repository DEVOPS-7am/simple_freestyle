pipeline {
    agent any 
    stages {
        stage ('git source') {
            steps {
                script {
                    'git clone https://github.com/DEVOPS-7am/simple_freestyle.git'
                }
                 
            }
        }
        stage ('build') {
            steps {
                script {
                    mvn clean install
                }
            }
        }
    }
}
