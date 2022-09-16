# https://docs.docker.com/registry/

```
docker run -d -p 5000:5000 --name registry registry:2
docker run -p 5000:5000 -v /home/registry:/var/lib/registry registry:2.7

docker push 127.0.0.1:5000/mybusybox:v1
docker pull 127.0.0.1:5000/mybusybox:v1
```