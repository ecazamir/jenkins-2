#!/usr/bin/env groovy
timestamps {
  stage ('Print Environment') {
    def envAll = getContext( hudson.EnvVars )
    echo envAll.collect{ k, v -> "$k = $v" }.join('\n')
  }
}
