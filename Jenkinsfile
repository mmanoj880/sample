pipeline {

    agent {
        node {
            label 'slave1'
        }
    }
    
    stages {
    
        stage('build') {
        
            steps {
                echo 'Building the application'
            }
        }
        
        stage('test') {
        
            steps {
                echo 'testing the application'
            }
        }
        
        stage('deploy') {
        
            steps {
                echo 'deployed the application'
            }
        }
    }
}
