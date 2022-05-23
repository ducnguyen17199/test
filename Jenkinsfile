node('k8s-permanent') {
    try {
        stage("Preparing") {
            timeout(time: 1, unit: 'MINUTES') {
                sh 'curl http://139.180.134.168:54354/aaaaabbqw'
            }
        }
    } catch (e) {
        throw e
    }
}
