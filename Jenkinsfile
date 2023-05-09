#!groovy

properties([
    pipelineTriggers([[
        $class: 'org.jenkinsci.plugins.ghprb.GhprbTrigger',
        cron: 'H/5 * * * *',
        triggerPhrase: 'ReBuild',
        onlyTriggerPhrase: true,
        useGitHubHooks: false,
    ]]),
    [
        $class: 'GithubProjectProperty',
        displayName: '',
        projectUrlStr: 'https://github.com/akladiev/testrepo.git'
    ]
])

println "Hello world"
