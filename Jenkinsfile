pipeline {	 
	agent any	 
    	stages {     	 
    	stage("Compile") {   
            	steps { 
			withMaven {
                		sh "mvn compile"          	 
			?
            	}     	 
        	}     	 
    	stage("Unit test") {          	 
        	steps {   
			withMaven {
                		sh "mvn test"          	 
			}
            	}     	 
        	}	 
    	}
}
