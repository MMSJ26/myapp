pipeline {
    agent any
    tools{
        maven "Maven"
        jdk "java8"
    }
    stages{
        stage('clone'){
            steps{
                git 'https://github.com/MMSJ26/myappsemexo2.git'
            }
        }
        stage('Build'){
            steps{
                sh 'mvn clean package'
            }
        }
    }
}
