#Kubernetes.

Note, the order in which you run files from thiis folder is actually very relelvant.
Please run the dependant files such as: mongosecret.yaml and storageclass.yaml before mongo values.
note to do the same for demo-deployment.yaml.
it depends on demo-secret.yaml
demo-configmap.yaml and for the nginx ingress controller. It is also dependant on demo-clusterip.yaml

(Please note the nginx is iffy. It only functions when in the same namespace as the app and demo-clusterip. I am working currently on resolving this.)
