frontend-dockerfile-imagepush-react--servuce
backend-dockerfile-imagepush--servuce
database-mongodb--pv-pvc--servuce

crashloopback --env files,helm charts-probes,
----hostnot found in upstream---service, frontend need to connect with backendas backend api contains service name in its conf file

portforward give & run in back ground ,in same tab we can run other commandds

mongodb uri in env in backend
jwttoken port for mongodb in env in backend deployment

in secrets you have to give encrypted value u can use online encrpyt base64

minikuda addons ingress
 lsof -i:80
 kubect portforward svc/backendservice 80:80 -n app

 kubectlm apply -f .
 --------
 nodeexporter---for every node and pod

 graphana password-----kubectl get secret \
  --namespace <your-namespace> \
  grafana \
  -o jsonpath="{.data.admin-password}" | base64 --decode ; echo
  =====
  same system you have kindcluster and eks then set kubectl use ckubectl config get-contexts
kubectl config use-context kind-kind
==============
=======================================================================================================================================================
MAIN PRJ


 
