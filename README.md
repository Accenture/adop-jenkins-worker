# Supported tags and respective Dockerfile links

- [`0.1.0`, `0.1.0` (*0.1.0/Dockerfile*)](https://github.com/Accenture/adop-jenkins-slave/blob/master/Dockerfile)

# What is adop-jenkins-slave?

adop-jenkins image provide Jenkins automation tool as a slave.

# How to use this image

The easiest for to run adop-jenkins-slace image is as follows:

docker run --name <your-container-name> -d accenture/adop-jenkins-slave:VERSION

Runtime configuration can be provided using environment variables:

* SWARM\_MASTER, URL for the jenkins instance acting as a master
* SWARM\_USER, username for connecting to master .
* SWARM\_PASSWORD, password for connecting to master.
* SLAVE\_NAME, Name for the Jenkins slave
* SLAVE\_LABELS, Whitespace-separated list of labels to be assigned for this slave.
* SLAVE\_MODE, The mode controlling how Jenkins allocates jobs to slaves.
* SLAVE\_EXECUTORS, Number of executors
* SLAVE\_DESCRIPTION, Description to be put on the slave

# License
Please view [licence information](LICENCE.md) for the software contained on this image.

#Supported Docker versions

This image is officially supported on Docker version 1.9.1.
Support for older versions (down to 1.6) is provided on a best-effort basis.

# User feedback

## Documentation
Documentation for this image is available in the [Jenkins documentation page](https://wiki.jenkins-ci.org/display/JENKINS/Home) and [Jenkins Swarm plugin documentation page](https://wiki.jenkins-ci.org/display/JENKINS/Swarm+Plugin). 
Additional documentaion can be found under the [`docker-library/docs` GitHub repo](https://github.com/docker-library/docs). Be sure to familiarize yourself with the [repository's `README.md` file](https://github.com/docker-library/docs/blob/master/README.md) before attempting a pull request.

## Issues
If you have any problems with or questions about this image, please contact us through a [GitHub issue](https://github.com/Accenture/adop-jenkins-slave/issues).

## Contribute
You are invited to contribute new features, fixes, or updates, large or small; we are always thrilled to receive pull requests, and do our best to process them as fast as we can.

Before you start to code, we recommend discussing your plans through a [GitHub issue](https://github.com/Accenture/adop-jenkins-slave/issues), especially for more ambitious contributions. This gives other contributors a chance to point you in the right direction, give you feedback on your design, and help you find out if someone else is working on the same thing.
