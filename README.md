# Kubernetes-ansible

## changeLog见本页的wiki界面
https://github.com/zhangguanzhang/Kubernetes-ansible/wiki

## 关于本项目(必看)
https://github.com/zhangguanzhang/Kubernetes-ansible/wiki/What-I-did

## ansible部署Kubernetes

系统可采用`Ubuntu 16.x`(未完成)与`CentOS 7.x`(建议7.x里使用最新的)
本次安裝的版本：
> * Kubernetes v1.16.4 (HA高可用)
> * CNI plugins v0.8.1
> * Etcd v3.3.14
> * flanneld v0.11.0
> * Calico (不写,可以自行去找yaml部署)
> * Docker CE 19.03

## 使用指南
### 部署前
https://github.com/zhangguanzhang/Kubernetes-ansible/wiki/Before-deploy

### 部署文档
https://github.com/zhangguanzhang/Kubernetes-ansible/wiki/Deploy

README信息后续更倾向于wiki页面更新，毕竟分支不再是一个

### kubectl get cs显示unkown不是bug,见
https://github.com/kubernetes/enhancements/issues/553
