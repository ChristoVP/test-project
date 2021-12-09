pipeline { 
    agent any  
    stages { 
        stage('Build') { 
            steps { 
               bat 'mvn clean install -PautoInstallPackage'
               echo 'This is a minimal pipeline.' 
            }
        }
    }
}
