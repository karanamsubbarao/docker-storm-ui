# Docker Storm UI

Run with:

```
docker run -d --name storm-ui -p 8080:8080 --restart always --link nimbus:nimbus --link docker-zookeeper:docker-zookeeper karanamsubbarao/docker-storm-ui
