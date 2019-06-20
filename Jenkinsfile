pipeline {
    agent any
    stages {
        stage('start') {
            steps {
                git(url: 'https://github.com/vc-rakesh/test.git', branch: 'master', credentialsId: 'ed3ca86c-3bbb-4b9f-8fd5-6e1553a9650d')
            }
        }
    }
}