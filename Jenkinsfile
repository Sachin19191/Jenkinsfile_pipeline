pipeline {

agent jenkins_build_maven

stages {
	stage('SCM') {
		steps {
			echo "git pull my code step1"
			git 'https://github.com/Sachin19191/maven_java_app.git'
		}
	}

	stage('Build') {
		steps {
			sh 'mvn clean package'
		

		}
	}	

	stage('Deploy') {
		steps {
			sh 'java -jar target/*.jar'
		}
	}

	}
}
 