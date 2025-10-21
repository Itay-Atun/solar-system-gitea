pipeline {
    agent any
    
    tools {
      nodejs 'nodejs-22-6-0'
    }

    stages {
        stage('Check NodeJS Version') {
            steps {
                sh node -v
                sh npm -v
            }
        }
    }
}
