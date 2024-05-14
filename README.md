## Agent-based Installer功能說明

#### 為管理和配置 Linux 系統網路狀態的工具

```
dnf install nmstate -y
```


#### OpenShift CLI 
```
curl -LO https://mirror.openshift.com/pub/openshift-v4/x86_64/clients/ocp/${OCP_VERSION}/openshift-install-linux.tar.gz
tar zxf openshift-install-linux.tar.gz
```
```
curl -LO https://mirror.openshift.com/pub/openshift-v4/x86_64/clients/ocp/${OCP_VERSION}/openshift-client-linux.tar.gz
tar zxf openshift-client-linux.tar.gz
```

- 功能:

1. 使用者透過SNO Agent Deploy 欄位點擊Actions啟動Templates進行申請VM。
   
- 圖表:
  
流程圖 | 註解
------|----
![Untitled-2024-01-02-1454](https://github.com/gary901213/dco_test/assets/103558648/f9ec02c9-1a3f-41ac-9f04-6f5b89dda972) | -

