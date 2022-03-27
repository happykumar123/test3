pipeline {
    agent any 
    stages {
        stage(" SCM Srinivas Checkout ") {
            steps {
                  git 'https://github.com/srinivas55/mavenproject.git'
                   }
            }
        stage(" SCM Checkout Santhosh REPO " ) {
            steps {
                git 'https://github.com/happykumar123/test3.git'
                stage("Build") {
            steps {
                echo " HELLOOOOOO "
                   }
            }
           }
    }
