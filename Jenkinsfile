pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh "npm pack" 
            }
        }
        stage('Test') { 
            steps {
                echo "test" 
            }
        }
        stage('Deploy') { 
            steps {
                sh "npm start" 
            }
        }
    }
}
