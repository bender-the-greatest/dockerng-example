Saltstack dockerng Example
==========================
A simple example showing how to use Saltstack to provision a node with a Gitlab-CE docker container.

* docker/setup.sls - Sets up Docker on the node. Currently written for Ubuntu.
* docker/test.sls - Provisions the node with the Gitlab-CE Docker container, and starts it with a local-bound directory.

