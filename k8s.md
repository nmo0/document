## gctl
### 连接到集群
```shell
gctl clusters connect -c [cluster]
```
## kubectl
### 列出所有服务
```
kubectl get svc,po -n [namespace]
```

### 查看日志
```
kubectl logs -f [pod] -n [namespace]
```
