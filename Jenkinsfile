pipeline { 
    agent any  
    stages { 
        stage('Build') { 
            steps { 
               bat 'mvn clean install -PautoInstallSinglePackage'
               echo 'This is a minimal pipeline.' 
            }
        }
    }
}
