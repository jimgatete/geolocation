pipeline{
    agent any
    tools {
        maven 'M2_HOME'
    }
    stages{
        stage('M2_HOME'){
            steps{
                sh 'mvn clean install package'
            }
        }
    }
}