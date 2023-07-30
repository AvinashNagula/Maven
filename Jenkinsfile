pipeline {
 agent any
   stages {
        stage('build') {
            steps {
               sh 'echo "Build from feature jenkins file"'
            }
        }
    }
  stages {
        stage('testing') {
            steps {
               sh 'echo "testing from feature jenkins file"'
            }
        }
    }
  stages {
        stage('prod') {
            steps {
               sh 'echo "Prod from feature jenkins file"'
            }
        }
    }
}
