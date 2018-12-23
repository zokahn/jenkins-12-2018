pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                    uname -a
                    hostname
                    date
                    ping -c 3 www.xs4all.nl
                '''
            }
        }
    }
}
