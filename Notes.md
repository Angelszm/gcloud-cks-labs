To add some google cloud notes (for k8s clusters list)


```
gcloud
gcloud auth login
gcloud projects list
gcloud config set project project_id
gcloud compute instances list

```

CKS K8s Cluster
```
- cks master
- cks worker 
- Machine Type : e2-meidum (2vCPU and 4GB Memory )
- Ubuntu 20.04
```

From Terminal : 
```
- gcloud compute ssh cks-master
    - install master 
- gcloud compute ssh cks-worker
    - install worker node sh 

And join kubeadm with master on worker node
```


To Open Ports between 30000~40000
```
gcloud compute firewall-rules create nodeports --allow tcp:30000-40000
```


Killer Code Access




