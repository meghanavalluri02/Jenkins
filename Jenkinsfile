pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git credentialsId: 'd6f0e3e2-9974-4f3f-83f5-00cd6296179c', branch: 'main', url: 'https://github.com/meghanavalluri02/Jenkins.git'
            }
        }
    }
}
