// Powered by Infostretch 

timestamps {

node () {

	stage ('pythonflask - Checkout') {
 	 checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '', url: 'https://github.com/srinanpravij/exercise.python_flask-heroku-deployment.git']]]) 
	}
	stage ('pythonflask - Build') {
 	
 	powershell "python web.py"
	}
}
}