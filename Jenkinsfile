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
        // stage('Deploy') {
        //     steps {
        //         echo 'Code Is Deploying'
        //     }
        }
    }
}