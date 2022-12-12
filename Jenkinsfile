pipeline {
	agent any 
		stages {
			stage ('Git Checkout') {
				steps {
					git branch: 'nader', url: 'https://github.com/Naderbenmrad/DevOps.git'
				}
			}
			stage ('Maven Build') {
				steps {
					sh 'mvn clean install'
				}
			}
			
		}
}
