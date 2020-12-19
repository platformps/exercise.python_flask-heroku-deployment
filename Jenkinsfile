// Powered by Infostretch

timestamps {

node () {

	stage ('python-flask - Checkout') {
 	 checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '', url: 'https://github.com/k-charette/exercise.python_flask-heroku-deployment.git']]])
	}
	stage ('python-flask - Build') {
 	    powershell "python web.py"
	}
}
}