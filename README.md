# Supported tags and respective Dockerfile links

- [`0.1.0`, `0.1.0` (*0.1.0/Dockerfile*)](https://github.com/Accenture/adop-jenkins-worker/blob/master/Dockerfile)

# What is adop-jenkins-worker?

adop-jenkins image provide Jenkins automation tool as a worker.

# How to use this image

The easiest for to run adop-jenkins-worker image is as follows:

docker run --name <your-container-name> -d accenture/adop-jenkins-worker:VERSION

Runtime configuration can be provided using environment variables:

* SWARM\_MASTER, URL for the jenkins instance acting as a primary
* SWARM\_USER, username for connecting to primary
* SWARM\_PASSWORD, password for connecting to primary
* SLAVE\_NAME, Name for the Jenkins worker
* SLAVE\_LABELS, Whitespace-separated list of labels to be assigned for this worker.
* SLAVE\_MODE, The mode controlling how Jenkins allocates jobs to workers.
* SLAVE\_EXECUTORS, Number of executors
* SLAVE\_DESCRIPTION, Description to be put on the worker

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
If you have any problems with or questions about this image, please contact us through a [GitHub issue](https://github.com/Accenture/adop-jenkins-worker/issues).

## Contribute
You are invited to contribute new features, fixes, or updates, large or small; we are always thrilled to receive pull requests, and do our best to process them as fast as we can.

Before you start to code, we recommend discussing your plans through a [GitHub issue](https://github.com/Accenture/adop-jenkins-worker/issues), especially for more ambitious contributions. This gives other contributors a chance to point you in the right direction, give you feedback on your design, and help you find out if someone else is working on the same thing.
