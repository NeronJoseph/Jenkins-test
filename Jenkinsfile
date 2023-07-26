/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello Neron"'
                sh '''
                    echo "This is a multiline shell"
                    echo "Bye"
                    pwd
                    ls -al
                '''
            }
        }
    }
}
