#!groovy

properties([
    parameters([
        booleanParam(defaultValue: true,
                     description: 'Cancel the rest of parallel stages if one of them fails and return status immediately',
                     name: 'failFast'),
        booleanParam(defaultValue: true,
                     description: 'Propagate status to GitHub',
                     name: 'propagateStatus'),
        string(defaultValue: '',
               description: 'Pipeline shared library version (branch/tag/commit). Determined automatically if empty',
               name: 'library_version')
    ])
    pipelineTriggers([
        issueCommentTrigger('.*build jenkins/ci pipeline.*')
    ])
])

println "Hello world"
