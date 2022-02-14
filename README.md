# nrpe-coreos

Run as follows:

```
podman run -d --restart unless-stopped --privileged --net=host --ipc=host --pid=host quay.io/agileio/nrpe-coreos:latest
```

Mount nrpe.cfg to /etc/nagios/nrpe.cfg
