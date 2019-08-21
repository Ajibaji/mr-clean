# Mr-Clean

A little tool to aid development of Kubernetes based services. 

Pulls and decodes K8 secrets in user selected namespaces, using ~/.kube/config 
credentials, providing devs with a quick way of:
 - dropping database content from any IP
 - opening PSQL shell into a selected database
 - opening BASH shell inside K8 cluster
