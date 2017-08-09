# Sonobuoy systemd-logs plugin

This is a simple standalone container that gathers log information from systemd, by chrooting into the node's filesystem and running `journalctl`.

This container is used by [Heptio Sonobuoy](https://github.com/heptio/sonobuoy) for gathering host logs in a Kubernetes cluster.
