# Flash Socket Policy Server Docker

This Docker container runs a simple perl script to serve a flash policy XML file. The script is from [Kira's Web Toolbox](http://www.lightsphere.com/dev/articles/flash_socket_policy.html).

To run the docker container:

```bash
docker run -d -p 843:843 adamlc/flash-socket-policy-docker
```
