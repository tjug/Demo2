pipeline{
    agent any
    stages{
        stage('init'){
            checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'eeec42e6-c7fe-4afd-8225-85247a6e32a7', url: 'https://github.com/tjug/Demo2.git']]])
        }
    }
}