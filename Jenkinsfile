pipeline {
    agent any 
    stages {
        stage("SCM Checkout ") {
            steps {
                git 'https://github.com/happykumar123/test3.git'
                git 'https://github.com/srinivas55/mavenproject.git'
                   }
            }
                stage("Build") {
            steps {
                mvn clean package
                   }
            }
           }
    }
