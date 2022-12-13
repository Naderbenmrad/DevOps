pipeline {
	agent any 
		stages {
			stage ('Git Checkout') {
				steps {
					git branch: 'nader', url: 'https://github.com/Naderbenmrad/DevOps.git'
				}
			}
			stage ('Maven Clean') {
				steps {
					sh 'mvn clean'
				}
			}
			stage ('Maven Compile') {
				steps {
					sh 'mvn compile'
				}
			}
			
		}
}
