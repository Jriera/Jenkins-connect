//create a jenkins file to build an angular project
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'ng build --prod'
            }
        }
    }
}
