# quay-fm-skill
Alexa skill for streaming Alderney's Quay FM radio

# Overview

This project is deployed as an Alexa-hosted skill, meaning that the lambda function is
provisioned under an Alexa developer account, and deployments are managed by pushing this git repo
to the Alexa developer console.

In order to fulfil the HTTPS requirements for streaming content on Alexa, the usual Quay FM stream
(http://stream.quayfm.gg:1071/live) has been proxied behind a TLS secured kubernetes ingress in my
[hobby-k8s project](https://github.com/briggySmalls/hobby-k8s).
