pipeline {	 
	agent any	 
    	stages {     	 
    	stage("Compile") {   
            	steps { 
			sh "echo $PATH"
                	sh "/usr/local/apache-maven/bin/mvn compile"          	 
            	}     	 
        	}     	 
    	stage("Unit test") {          	 
        	steps {   
               		sh "/usr/local/apache-maven/bin/mvn test"          	 
            	}     	 
        	}	 
    	}
}
