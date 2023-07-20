pipeline {
 agent any
   stages {
        stage('build') {
            steps {
               sh 'apt install maven -y'
               sh 'mvn clean pack'
            }
        }
    }
}
