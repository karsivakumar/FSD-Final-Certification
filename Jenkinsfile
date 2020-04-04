pipeline {
    agent any
       environment {
       color = "blue"
   }
    stages {
        stage('GIT checkout') {
            steps {
                echo 'Checkout from SCM'
                git 'https://github.com/karsivakumar/FSD-Final-Certification'
            }
        }
    }
}
