pipeline {
    agent any

    stages {
        stage ('changing the file permission') {
            steps {
                sh ' chmod +x build_anish.sh'
            }
        }

        stage ('executing the file') {
            steps {
                sh './build_anish.sh'
            }
        }
    }
}
