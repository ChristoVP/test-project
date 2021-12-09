pipeline { 
    agent any  
    stages { 
        stage('Build') { 
            steps { 
               bat 'mvn clean install'
               echo 'This is a minimal pipeline.' 
            }
        }
    }
}
