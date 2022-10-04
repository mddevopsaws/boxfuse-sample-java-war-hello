node('built-in') {    
   stage('Continous Download') {    
    git changelog: false, credentialsId: 'e2136f12-42ae-4a79-846e-0cbb01fdbb13', poll: false, url: 'https://github.com/mddevopsaws/boxfuse-sample-java-war-hello.git'
     }
    stage('Continous Build') {    
		sh 'mvn package'
	}
	
    stage('Continous Deployment') {
		sh 'echo "Deployment Passed"'
        }
  
}
