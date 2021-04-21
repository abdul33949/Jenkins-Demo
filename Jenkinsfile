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
            }
            steps {
                echo 'Code Is Deploying'
            }
        }
    }
}

https://oak9io.webhook.office.com/webhookb2/b7301e65-a298-4abf-b1a0-5434d8d1a641@ad5732e0-3498-43d6-a88a-97e995051090/IncomingWebhook/a556cbbcee4240719b806ca882045483/0bccf2ea-23b0-461f-8073-71e3db842b06
