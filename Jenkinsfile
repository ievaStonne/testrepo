#!groovy

job('example') {
    triggers {
        githubPullRequest {
            triggerPhrase('OK to test')
            onlyTriggerPhrase()
        }
    }
    stages {
        stage('test') {
            steps {
                script {
                    println "hello"
                }
            }
        }
    }
}
