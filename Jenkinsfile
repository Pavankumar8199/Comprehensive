pipeline {
    agent any
    stages {
        stage('git repo & clean') {
            steps {
                bat "rmdir /s /q Employee-Management-Testing"
                bat "git clone https://github.com/Pavankumar8199/Comprehensive.git"
                bat "mvn clean -f Employee-Management-Testing"
            }
        }
        stage('install') {
            steps {
                bat "mvn install -f Employee-Management-Testing"
            }
        }
        stage('test') {
            steps {
                bat "mvn test -f Employee-Management-Testing"
            }
        }
        stage('test') {
            steps {
                bat "mvn test -f Employee-Management-Testing"
            }
        }
        }
}
