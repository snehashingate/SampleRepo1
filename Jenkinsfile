pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                archiveArtifacts artifacts: 'test.txt', fingerprint: true
                cleanWs()
            }
        }
    }
}
