#!groovy

properties([
    pipelineTriggers([[
        $class: 'org.jenkinsci.plugins.ghprb.GhprbTrigger',
        cron: 'H/5 * * * *',
        triggerPhrase: 'ReBuild',
        onlyTriggerPhrase: true,
        useGitHubHooks: false,
        orgslist: 'openvinotoolkit',
        allowMembersOfWhitelistedOrgsAsAdmin: true,
    ]]),
    [
        $class: 'GithubProjectProperty',
        displayName: '',
        projectUrlStr: 'https://github.com/akladiev/testrepo'
    ]
])

println "Hello world"
