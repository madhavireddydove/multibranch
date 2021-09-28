pipeline { 
  
   agent any

   stages {
   
     stage('checkout') { 
        steps { 
           echo "code checkingout"
        }
     }
       stage('build') { 
        steps { 
           echo "code building"
        }
     }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
