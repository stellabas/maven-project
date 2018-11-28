pipeline {
    agent any
    stages{
       stage('Build'){
            steps{
                sh 'mvn clean packeage'
                sh "docker build . -t tomcatewbapp: ${env.BUILD_ID}"
            }


       }

    }

}