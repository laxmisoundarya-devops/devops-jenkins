pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh 'echo "My first pipeline"'
                sh '''
                     echo "more line in one stage"
                     ls -latr
                     
                '''
                echo 'building the application' 
            }
        }
        
    }
}
