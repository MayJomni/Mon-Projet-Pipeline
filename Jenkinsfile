pipeline {
    agent any

    stages {
        stage('Git - Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/MayJomni/Mon-Projet-Pipeline.git'
            }
        }

        stage('Maven - Version') {
            steps {
                sh 'mvn -version'
            }
        }
    }
}
