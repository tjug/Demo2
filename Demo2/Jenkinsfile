pipeline{
agent any
stages{

    stage('Initialize'){
        env.PATH = "${tool 'maven'}/usr/bin:${env.PATH}"
    }
    stage('Checkout'){
        git 'https://github.com/tjug/Demo2'
    }
    stage('Build'){
        sh 'mvn clean package'
    }

}