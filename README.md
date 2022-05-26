# helm-chart

## helm的chart仓库地址为：https://maikoulin.github.io/helm-chart/

## 本Chart仓库的使用方法

1、添加chart仓库
```
# helm repo add myrepo https://maikoulin.github.io/helm-chart
```

2、添加成功
```
# helm repo list
NAME  	URL                                   
myrepo	https://maikoulin.github.io/helm-chart
```

3、搜索chart包
```
# helm search repo


4、安装chart包
```
# helm install xxx myrepo/test
```

xxx为relaese名字
