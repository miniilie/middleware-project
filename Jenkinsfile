pipeline {
    agent any

    stages{
        stage("create zip file"){
            steps{
               
           sh 'zip middlewasreScript-${BUILD_NUMBER}.zip *  --exclude Jenkinsfile README.md '  
            
            }
        }
        
    }
    stages{
        stage("test"){
            steps {
                echo "hehehe we are here "
            }
            
        }
    }
        
    
}