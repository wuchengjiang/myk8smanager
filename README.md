# K8S多集群管理和项目CI/CD部署到K8S


## 主要功能

包括: K8S多集群管理，装机平台，资产管理，自动化发布，VPN账号管理，资产报表

## 开发语言

 gin-vue-admin框架,client-go 客户端 
   
## 架构设计
 
 1. gin-vue-admin 集成了用户管理、角色管理、授权管理、菜单管理、附件上传、API管理、Casbin管理 ，前端集成了vue的Element-UI 即插即用

 2. K8S集群管理通过client-go客户端管理k8s的资源

 3. CI/CD 流水线 集成 tekton 用于项目的持续构建 ,argocd 用于项目的gitops发布

## 系统展示

**k8s多集群管理**

![](https://raw.githubusercontent.com/wuchengjiang/myk8smanager/main/images/k8s%E5%A4%9A%E9%9B%86%E7%BE%A4%E7%AE%A1%E7%90%86.png)

**dashboard**
![](https://raw.githubusercontent.com/wuchengjiang/myk8smanager/main/images/dashboard.png)

**k8s 资源管理**
![](https://raw.githubusercontent.com/wuchengjiang/myk8smanager/main/images/k8s%20deployment%E7%AE%A1%E7%90%86.png)

![](https://raw.githubusercontent.com/wuchengjiang/myk8smanager/main/images/service%E7%AE%A1%E7%90%86.png)

![](https://raw.githubusercontent.com/wuchengjiang/myk8smanager/main/images/pod%E7%AE%A1%E7%90%86.png)

**pipeline流水线**

![](https://raw.githubusercontent.com/wuchengjiang/myk8smanager/main/images/%E6%9E%84%E5%BB%BA%E8%AE%A1%E5%88%92.png)

![](https://raw.githubusercontent.com/wuchengjiang/myk8smanager/main/images/%E6%9E%84%E5%BB%BA%E5%8F%82%E6%95%B0.png)


