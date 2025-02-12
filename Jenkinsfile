pipeline {  
    agent any  
    stages {  
        stage("Install Dependencies") {  
            steps {  
                bat 'npm install'  
            }  
        }
         stage("Start app") {  
            steps {  
                bat 'start npm start'  
            }  
        }  
        stage("Run Tests") {  
            steps {  
                bat 'npm test'  
            }  
        }  
    }  
}