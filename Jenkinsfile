pipeline {
		agent any
		stages {
			stage("Build"){
				steps {
				sh "mvn clean install"
				}
			}
			stage("Test"){
			   steps {
			   sh "echo testing"
			   }
			}
			
			stage("Deploy"){
				steps {
				sh "echo Deploy"
				sh "echo completed"
				}
			}
		}
}
