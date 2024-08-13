pipeline {
    agent any

    stages {
        stage('Build_stage') {
            steps {
                echo 'Building'
            }
        }
        stage('Test_stage') {
            steps {
                echo 'Testing'
            }
        }
        stage('Deploy_stage') {
            steps {
                echo 'Deploying'
            }
        }
    }

    post {
        always {
            echo 'Thank you'
        }
    }
}
