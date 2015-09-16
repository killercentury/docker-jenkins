# Jenkins with Docker Engine and Compose

Usage for EC2
```
docker run -v /var/run/docker.sock:/var/run/docker.sock -v $(which docker):/bin/docker -v /lib64/libdevmapper.so.1.02:/lib/libdevmapper.so.1.02:ro -v /lib64/libudev.so.0:/lib/libudev.so.0:ro --name jenkins -d jenkins-generic
```
