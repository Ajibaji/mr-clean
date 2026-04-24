# Mr-Clean

A little tool to aid development of Kubernetes based services.

Pulls and decodes K8s secrets in user selected namespaces, using `~/.kube/config`
credentials, providing devs with a convenient way of:
 - opening a BASH shell inside K8s cluster
 - opening a PSQL shell into a selected database from within the target namespace
 - dropping postgres database content inside the K8s cluster from any IP

Mr-Clean is auto-updating

## Install
```curl https://raw.githubusercontent.com/Ajibaji/mr-clean/master/install | bash```



## Coming soon:
 - trailing logs from user-selected pods in a user-selected namespace 
 - port-forwarding and CORS mitigation for local development of front & backend 
   services without deploying to K8
