pipeline {
    agent any
    stages {
        stage('Checkout Code') {
            steps {
               git branch: 'main', credentialsId: 'Jenkins_ssh', url: 'git@github.com:codewithabhi-ops/java_web_app.git'
                  
            }
        }
    }
}
