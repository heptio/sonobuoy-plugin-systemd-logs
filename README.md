# Sonobuoy systemd-logs plugin

> NOTE: This repository is no longer actively maintained. The project has moved to [github.com/vmware-tanzu/sonobuoy-plugins](https://github.com/vmware-tanzu/sonobuoy-plugins)

This is a simple standalone container that gathers log information from systemd, by chrooting into the node's filesystem and running `journalctl`.

This container is used by [Heptio Sonobuoy](https://github.com/heptio/sonobuoy) for gathering host logs in a Kubernetes cluster.
