pipeline {
 agent any
   stages {
        stage('build') {
            steps {
               sh 'yum install maven -y'
               sh 'mvn clean pack'
            }
        }
    }
}
