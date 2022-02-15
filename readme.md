将这几个文件移动到/usr/bin目录，或者通过ln建立快捷方式
```
mv helm /usr/bin/helm
mv kubectl /usr/bin/kubectl 
mv rancher /usr/bin/rancher
mv rke_linux-arm64 /usr/bin/rke
```
添加指定k8s的配置文件，可以放到/root/.kube/目录下，名称是config，内容可以到rancher集群里下载

export KUBECONFIG=/root/.kube/config
```
helm version
helm create hello
helm install ./hello
```

