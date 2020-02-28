## how to deploy ?

  1. get SERVICE_CLUSTER_IP_RANG / CLUSTER_DNS_IP / CLUSTER_DOMAIN values from `kubelet.config` and `apiserver.config` 
  2. exec cmd
```
./deploy.sh -r $SERVICE_CLUSTER_IP_RANG -i $CLUSTER_DNS_IP  -d $CLUSTER_MOMAIN -s |kubectl apply -f - 
```
