pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "npm pack" 
            }
        }
        stage('Test') { 
            steps {
                echo "test" 
            }
        }
        stage('Deploy') { 
            steps {
                echo "npm start" 
            }
        }
    }
}
