# pause

拉取 k8s.gcr.io 镜像

```shell
docker push kainonly/pause:3.1
// or
docker pull ccr.ccs.tencentyun.com/kainonly/pause:3.1
```

重命名镜像

```shell
docker tag kainonly/pause:3.1 k8s.gcr.io/pause:3.1
// or
docker tag ccr.ccs.tencentyun.com/kainonly/pause:3.1 k8s.gcr.io/pause:3.1
```

删除镜像

```shell
docker rmi kainonly/pause:3.1
// or
docker rmi ccr.ccs.tencentyun.com/kainonly/pause:3.1
```