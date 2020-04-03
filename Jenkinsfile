pipeline {
    agent any
       environment {
       color = "blue"
   }
    stages {
//        stage('GIT checkout') {
//            steps {
//                echo 'Checkout from SCM'
//                git 'https://github.com/karsivakumar/FSD-Final-Certification'
//            }
//        }
//        stage('Build Task Manager Frontend') {
//            steps {
//                echo 'Building Task Manager Frontend..'
//                bat 'cd ./TaskManagerFrontend/ && npm install && npm run build --prod'
//            }
//        }
//        stage('Build Task Manager Backend') {
//            steps {
//                echo 'Building Task Manager Backend ..'
//                bat 'cd ./TaskManagerBackend/ && npm install --no-optional && npm run build'
//            }
//        }
//        stage('Testing Task Manager Frontend') {
//            steps {
//                echo 'Testing Task Manager Frontend...'
//                bat 'TaskManagerBackend/node_modules/.bin/pm2 start ./TaskManagerBackend/index.js -f'
//                bat 'cd ./TaskManagerFrontend/ && npm test --single-run true --watch=false'
//                bat 'TaskManagerBackend/node_modules/.bin/pm2 stop index'               
//            }
//        }
//        stage('Testing Task Manager Backend') {
//            steps {
//                echo 'Testing Backend...'
//                bat 'cd ./TaskManagerBackend/ && npm test'
//            }
//        }
    stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                bat 'dockerx ps -a'
            }
        }
    }
}
