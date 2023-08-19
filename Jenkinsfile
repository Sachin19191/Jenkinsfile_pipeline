pipeline {

agent linuxnodemvn

stages {
	stage('SCM') {
		steps {
			echo "git pull my code step1"
			echo "git pull my code step2"s
			git 'https://github.com/Sachin19191/maven_java_app.git'
		}
	}

	stage('Build') {
		steps {
			sh 'mvn clean package'
			echo "maven build package"

		}
	}	

	stage('Test') {
		steps {
			echo "test my final webapp" 
		}
	}

	}
}
 