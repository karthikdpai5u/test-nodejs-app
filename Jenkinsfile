npipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'sudo apt install npm -y' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'npm --version"'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
