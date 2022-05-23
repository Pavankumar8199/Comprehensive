pipeline {
    agent any
    tools{
        maven 'MAVEN'
        
    }
    stages{
        
        stage("Maven Build"){
            steps{
                bat 'mvn-Dmaven.test.failure.ignore=true clean package'
            }
        }
        
    }
}

