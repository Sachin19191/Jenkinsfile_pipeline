pipeline {

agent any

stages {
	stage('SCM') {
		steps {
			echo "git pull my code step1"
			echo "git pull my code step2"
			git 'https://github.com/Sachin19191/maven_java_app.git'
		}
	}

	stage('Deploy') {
		steps {
			 echo "deploying my code"
		}
	}	

	stage('Test') {
		steps {
			echo "test my final webapp" 
		}
	}

	}
}
 