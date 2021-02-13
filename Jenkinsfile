pipeline {	 
	agent any	 
    	stages {     	 
    	stage("Compile") {   
            	steps { 
			withMaven(my_maven) {
                		sh "mvn compile"          	 
			}
            	}     	 
        	}     	 
    	stage("Unit test") {          	 
        	steps {   
			withMaven(my_maven) {
                		sh "mvn test"          	 
			}
            	}     	 
        	}	 
    	}
}
