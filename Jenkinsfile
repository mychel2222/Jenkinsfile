pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                // Menggunakan path lengkap agar Windows / Jenkins mengenali perintah docker
                bat '"C:\\Program Files\\Docker\\Docker\\resources\\bin\\docker.exe" build -t mychelmunthe/munthe:latest .'
            }
        }
    }
}
