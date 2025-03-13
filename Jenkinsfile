pipeline {
    agent any
    
    stages {
        stage('Clone Repository') {
            steps {
                script {
                    sh 'pipeline {
    agent any
    
    stages {
        stage('Clone Repository') {
            steps {
                script {
                    sh 'git clone https://github.com/MMG159/PES1UG22CS313_Jenkins.git'
                }
            }
        }
        
        stage('Build') {
            steps {
                script {
                    sh 'g++ -o PES1UG22CS313 PES1UG22CS313_Jenkins/working.cpp'
                }
            }
        }
        
        stage('Test') {
            steps {
                script {
                    sh './PES1UG22CS313'
                }
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'deploy'
                // Add deployment steps here
            }
        }
    }
    
    post {
        failure {
            echo 'pipeline failed'
        }
    }
}'
                }
            }
        }
        
        stage('Build') {
            steps {
                script {
                    sh 'g++ -o PES1UG22CS313 PES1UG22CS313_Jenkins/working.cpp'
                }
            }
        }
        
        stage('Test') {
            steps {
                script {
                    sh './PES1UG22CS313'
                }
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'deploy'
                // Add deployment steps here
            }
        }
    }
    
    post {
        failure {
            echo 'pipeline failed'
        }
    }
}
