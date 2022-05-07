pipeline {
    agent any
    stages {
        stage('Example Username/Password') {
            environment {
                SERVICE_CREDS = credentials('BindCredentials')
            }
            steps {
                sh 'echo "Service user is $SERVICE_CREDS_USR"'
                sh 'echo "Service password is $SERVICE_CREDS_PSW"'
                sh 'echo "Service user is $env.SERVICE_CREDS_USR"'
                sh 'echo "Service password is $env.SERVICE_CREDS_PSW"'
            }
        }
    }
}
