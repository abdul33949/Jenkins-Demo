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
            steps {
                echo 'Code Is Testing'
            }
        }
        stage('Deploy') {
              when {
                branch 'master'
                environment name: 'DEPLOY_TO', value: 'master'
            }
            steps {
                echo 'Deploying'
            }
        }
    }
}
