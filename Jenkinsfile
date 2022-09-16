pipeline {
    agent any

    stages {
        stage('Stage1:Build') {
            steps {
                echo "THis is Build Stage"
                sh 'sleep 5'             
            }
        }
        stage('Stage2:Push') {
            steps {
                echo 'This is Push Stage'
                sh 'sleep 5'
            }
        }
        stage('Stage3:Deploy') {
            steps {
                echo 'This is Deploy Stage'
                sh 'sleep 5'
            }
        }
    }
}    
