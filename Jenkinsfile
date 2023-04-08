pipeline {
  agent any
  tools { 
        maven 'Maven_3.8.4'  
    }
   stages{
    stage('CompileandRunSonarAnalysis') {
            steps {	
		sh 'mvn clean verify sonar:sonar -Dsonar.projectKey=jason-cloud-1 -Dsonar.organization=Jason -Dsonar.host.url=https://sonarcloud.io -Dsonar.login=
        } 
  }
}
