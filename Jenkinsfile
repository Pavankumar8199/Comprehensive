pipeline{
    agent any
    tools{
        maven 'MAVEN_HOME'
        
    }
    stages{
        
        stage('Maven Build'){
            steps{
                bat "mvn-Dmaven.test.failure.ignore=true clean package"
            }
        }
    }
}
