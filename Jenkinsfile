#!groovy

properties([
    pipelineTriggers([[
        $class: 'org.jenkinsci.plugins.ghprb.GhprbTrigger',
        cron: 'H/5 * * * *',
        triggerPhrase: 'ReBuild',
        onlyTriggerPhrase: true,
        useGitHubHooks: false,
    ]])
])

println "Hello world"
