pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'npm install' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy application from testing") { 
         steps { 
           sh 'echo "deploying application from testing..."'
         }

     }
  
   	}

   }
