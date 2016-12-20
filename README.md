# autossh-docker
A Dockerfile and start script to run autossh with reverse tunnels, based on Alpine linux.

Add the list of port in the tunnels, one tunnel per line in the openssh format:

```bash
LOCALPORT:REMOTEHOST:REMOTEPORT
```
<example>
8080:localhost:80
</example>

This line will bind pot 8080 on the docker container to port 80 on the remote server

