pipeline { 
    agent any  
    stages { 
        stage('Build') { 
            steps { 
                sh 'mvn clean install'
               echo 'This is a minimal pipeline.' 
            }
        }
    }
}
