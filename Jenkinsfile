pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                bat '"C:\\Program Files\\Docker\\Docker\\resources\\bin\\docker.exe" build -t mychelmunthe/munthe:%BUILD_NUMBER% .'
            }
        }
    }
}
