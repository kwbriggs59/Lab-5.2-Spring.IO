pipeline {	 
	agent any	 
    	stages {     	 
    	stage("Compile") {   
            	steps { 
			sh "export JAVA_HOME=/usr/lib/jvm/java-11-openjdk-amd64"
			sh "export M2_HOME=/usr/local/apache-maven"
                        sh "export MAVEN_HOME=/usr/local/apache-maven"
                        sh "export PATH=${M2_HOME}/bin:${PATH}"
                	sh "mvn compile"          	 
            	}     	 
        	}     	 
    	stage("Unit test") {          	 
        	steps {   
 			sh "export JAVA_HOME=/usr/lib/jvm/java-11-openjdk-amd64"
			sh "export M2_HOME=/usr/local/apache-maven"
                        sh "export MAVEN_HOME=/usr/local/apache-maven"
                        sh "export PATH=${M2_HOME}/bin:${PATH}"
               		sh "mvn test"          	 
            	}     	 
        	}	 
    	}
}
