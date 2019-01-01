This ros2 docker file is refering the ros docker from [vnc-ros-kinetic-full](https://hub.docker.com/r/ct2034/vnc-ros-kinetic-full/)

```
docker pull beandrewang/vnc-ros2-desktop:ardent
```

```
docker run -it --rm -p 6080:80 beandrewang/vnc-ros2-desktop:ardent
```

![](https://github.com/beandrewang/docker-vnc-ros2-desktop/blob/master/ardent/screenshot/ardent-desktop.png)