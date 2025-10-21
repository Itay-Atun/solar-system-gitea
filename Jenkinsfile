pipeline {
    agent any
    
    tools {
      nodejs 'nodejs-22-6-0'
    }

    stages {
        stage('Check NodeJS Version') {
            steps {
                node -v
                npm -v
            }
        }
    }
}
