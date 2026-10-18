pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                // Memanggil Docker dengan path absolut lengkap di Windows
                bat 'C:\\Program\\ Files\\Docker\\Docker\\resources\\bin\\docker.exe build -t mychelmunthe/munthe:latest .'
            }
        }
    }
}
