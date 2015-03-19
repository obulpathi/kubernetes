# kubernetes

The Container Manager

## Architecture
* Master: the managing machine, which oversees one or more minions.
* Minion: a slave that runs tasks as delegated by the user and Kubernetes master.
* Pod: an application (or part of an application) that runs on a minion. This is the basic unit of manipulation in Kubernetes.
* Replication Controller: ensures that the requested number of pods are running on minions at all times.
* Label: an arbitrary key/value pair that the Replication Controller uses for service discovery
* kubecfg: the command line config tool
* Service: an endpoint that provides load balancing across a replicated group of pods
