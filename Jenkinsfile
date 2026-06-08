pipeline {
    agent {
        label 'Built-In Node'
    }

    stages {

        stage('BUILD') {
            steps {
                sh 'echo "this is first stage in pipeline job"'
                sh 'ls -lrt'
            }
        }

        stage('TEST') {
            steps {
                sh '''
                    echo "this is second stage in pipeline job"
                    du -h
                '''
            }
        }
    }
}
