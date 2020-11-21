pipeline {
    agent {
        docker { image 'alpine' }
    }
    stages {
        stage('Hello') {
            steps {
                sh 'echo "Hello, world!"'
            }
        }
    }
}
