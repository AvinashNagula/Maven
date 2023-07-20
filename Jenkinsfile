pipeline {
 agent any
   stages {
        stage('build') {
            steps {
               sh 'sudo apt install maven -y'
               sh 'mvn clean pack'
            }
        }
    }
}
