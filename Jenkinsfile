pipeline {	 
	agent any	 
    	stages {     	 
    	stage("Compile") {   
            	steps { 
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
