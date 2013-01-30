This plugin is written for the Jenkins plugin tutorial,
and hence it's only useful as an example, and no other
practical use.

http://wiki.jenkins-ci.org/display/JENKINS/Plugin+tutorial

Plugin can be built using Gradle (see https://wiki.jenkins-ci.org/display/JENKINS/Gradle+JPI+Plugin). Useful build commands are:
* gradle clean jpi - to build the plugin in the build/ directory
* gradle test - Run unit tests
* gradle server - to run up an instance of Jenkins with your plugin

TODO
* Try adding some Scala code
* Combine with Gradle Release plugin (https://github.com/townsfolk/gradle-release)

