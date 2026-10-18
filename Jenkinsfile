pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                // Menggunakan PowerShell untuk menjalankan Docker
                powershell '"C:\\Program Files\\Docker\\Docker\\resources\\bin\\docker.exe" build -t mychelmunthe/munthe:latest .'
            }
        }
    }
}
