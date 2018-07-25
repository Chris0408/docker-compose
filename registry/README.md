# 未采用https加密时，需要使用私有仓库的宿主机，需要在/etc/docker/daemon.json进行配置，新增如下参数：
```
"insecure-registries": ["registry.test.com"]
```
