docker-nginx-as-root-hack
=========================

Dockerfile for running nginx as root

Kubernetes
----------

Obviously this is not the most secure setup. The main reason for this
quick hack is that Kubernetes appears to mount "emptyDir" volumes as
root:root 750. This means it does not even work for reading.

This hack at least got me up and running as a demo.


