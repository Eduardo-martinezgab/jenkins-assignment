pipeline {
    agent {
        docker {
            image 'ubuntu'
        }
    }

    stages {
        stage('Run') {
            steps {
                sh 'echo Running in Docker container'
                sh 'sleep 120'
            }
        }
    }
}