pipeline {
    agent any
         stages
	   {
             stage('git fetch repo')
	      {
                 steps 
		      {
			script
			      {
                                git branch: 'imtyaz', url: 'https://github.com/Munna7867/maven-web-application.git'
			       }
		         }
                   }
                }
              }
