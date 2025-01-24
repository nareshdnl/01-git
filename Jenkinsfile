pipeline {
  agent any
  stages {
        stage('Git Checkout') {
            steps {
               git branch: 'main', url: 'https://github.com/nareshdnl/01-git.git'
            }
        }
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
