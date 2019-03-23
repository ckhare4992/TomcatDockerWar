pipeline {
    agent { docker 'apache_maven-3.3.9' }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
