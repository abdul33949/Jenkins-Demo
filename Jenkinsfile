pipeline {
    agent any
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') {
            steps {
                echo 'Code Is Building'
            }
        }
        stage('Test') {
            when {
                branch 'master'
            }
            steps {
                echo 'Code Is Testing'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Code Is Deploying Yeepiiii-Test'
            }
        }
    }
}
