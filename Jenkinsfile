Jenkinsfile (Declarative Pipeline)
pipeline {
    agent any
    stages {
        stage('Deploy') {
            steps {
                retry(3) {
                    echo 'Helo'
                }

                timeout(time: 3, unit: 'MINUTES') {
                    echo 'jenkins'
                }
            }
        }
    }
}
