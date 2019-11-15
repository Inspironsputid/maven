pipeline {
   agent any

   stages {
      stage ('compile stage') {
         steps {
	         sh 'mvn clean compile'
	       }
	    }

      stage ('testing stage') {
         steps {
                 sh 'mvn test'
	       }
	     }
	   
      stage ('Deployment stage') {
         steps {
                 sh 'mvn deploy'
	       }
	     }
	  }
}
