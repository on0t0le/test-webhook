node('slave1') {
  stage('Preparing') {       
    git 'https://github.com/on0t0le/test-webhook.git'
  }
  stage('Hello from where'){
    def host = sh(script:'cat /etc/hostname',returnStdout:true)
    echo "Greatings from ${host}!"
  }
}
