pipeline{
agent any
stages{


    stage('Checkout'){
        git 'https://github.com/tjug/Demo2'
    }
    stage('Build'){
        sh 'mvn clean package'
    }

}
}