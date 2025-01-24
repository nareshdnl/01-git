pipeline {
  agent any
  stages {
    stage('git version') {
      steps {
        sh 'git --version'
      }
    }
    stage('java version') {
      steps {
        sh 'java -version'
        
      }
    }
	stage ('Checking OS version') {
	 steps {
	  sh 'uname -a ; df -h'
	 
		}
	}
		
	
  }
}
