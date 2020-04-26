pipeline {
    agent {
        label 'Linux_Slave1'
    }

    stages {
        stage('git') {
            steps{
              checkout scm 
            }
        }
        stage('Build') {
            steps {
                sh 'mvn compile package install' 
            }
        }
        stage('copying to local') {
            steps {
                sh 'cp target/*.war /home/ubuntu/builds'
            }
        }
    }
}
