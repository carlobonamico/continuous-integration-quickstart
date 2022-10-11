# Continuous Integration Quickstart
Introduction to Continuous Integration as a _Technical Practice_ (which you could also follow manually).

Examples with Jenkins as an _enabling tool_.

Continuous Integration > Jenkins

----
## Requirements
Java 11
* https://adoptium.net/temurin/releases?version=11

----
## Getting Started 
Download Jenkins LTS WAR
* https://www.jenkins.io/download/

----
## Security Warning
_With great power comes great responsibility_

Jenkins is an extremely powerful tool, able to: 
* access to source code
* execute potentially arbitrary commands
* generate binaries which get deployed in your environments

which open to both Supply Chain and command execution attacks.

Security __must__ be a primary concern
* defaults have greatly improved, but are not enough
* see https://www.jenkins.io/doc/book/security/

----
## Continuous Integration
https://martinfowler.com/articles/continuousIntegration.html

----
## The Ten Principles
https://www.slideshare.net/carlo.bonamico/continuous-integration-with-hudson

----
## From Hudson to Jenkins
Kohsuke Kawaguchi
https://github.com/kohsuke

Not just Jenkins
* Stapler (great grandparent of JAXRS)
* myriad of libraries and tools

----
## Next steps
Jenkins Pipelines (& Blue Ocean UI)
https://www.jenkins.io/doc/book/pipeline/

----
## References

https://www.slideshare.net/carlo.bonamico/continuous-integration-with-hudson

https://maven.apache.org/download.cgi
https://dlcdn.apache.org/maven/maven-3/3.8.6/binaries/apache-maven-3.8.6-bin.zip

----
## With Docker

docker pull jenkins/jenkins:lts-jdk11

https://hub.docker.com/r/jenkins/jenkins

