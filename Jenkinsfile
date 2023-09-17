pipeline {
    agent any
    stages {
        stage('Example Build') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Test') {
      steps {
        echo 'Testing...'
        snykSecurity(
          snykInstallation: 'synk',
          snykTokenId: 'SnykToken',
          // place other parameters here
        )
      }
    }
        stage('Example Deploy') {
            when {
                branch 'production'
            }
            steps {
                echo 'Deploying'
            }
        }
    }
}
