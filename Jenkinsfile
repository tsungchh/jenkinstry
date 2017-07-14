node { 
    git url: 'https://github.com/tsungchh/jenkinstry.git'
    properties([pipelineTriggers([[$class: 'GitHubPushTrigger'], pollSCM('H/15 * * * *')])])
    echo 'Hello World' 
}