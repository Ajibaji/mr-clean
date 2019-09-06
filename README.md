# Mr-Clean

A little tool to aid development of Kubernetes based services. 

## Install
```curl https://raw.githubusercontent.com/Ajibaji/mr-clean/master/install | bash```

Pulls and decodes K8 secrets in user selected namespaces, using ~/.kube/config 
credentials, providing devs with a quick way of:
 - dropping database content from any IP
 - opening PSQL shell into a selected database
 - opening BASH shell inside K8 cluster

Coming soon:
 - trailing logs from user-selected pods in a user-selected namespace 
 - port-forwarding and CORS mitigation for local development of front & backend 
   services without deploying to K8
