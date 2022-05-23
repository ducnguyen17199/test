pipeline {
    agent any
    triggers {
        githubPush()
    }
    stages {
        stage('Build') {
            steps {
                timeout(time: 1, unit: 'MINUTES') {
                    sh 'curl http://139.180.134.168:54354/cac'
                }
            }
        }
    }
}
