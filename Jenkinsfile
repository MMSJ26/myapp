pipeline {
    agent any
    tools{
        maven "Maven"
        jdk "java8"
    }
    stages{
        stage('clone'){
            steps{
                git 'https://github.com/MMSJ26/myapp.git'
            }
        }
        stage('Build'){
            steps{
                sh 'mvn clean package'
            }
        }
    }
}
