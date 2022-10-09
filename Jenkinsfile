pipeline{
  agent { label ' NODEJ1-JDK11' }
  stages {
    stage{
	  steps{
	    git branch: 'main', url: 'https://github.com/rajagithub18/spring-petclinic.git'
            sh 'mvn package'		
	  }
	}
  
  }
}
