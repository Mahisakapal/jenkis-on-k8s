# jenkis-on-k8s
## create a deplyment and sservice using this mainifast
## than access jenkins secret key 
'kubectl exec  -n jenkins jenkins-655f99d864-kpfs5 -- /bin/bash -c "cat /var/jenkins_home/secrets/initialAdminPassword"'
kubectl exec  -n <nmespase> <pod> -- /bin/bash -c "cat /var/jenkins_home/secrets/initialAdminPassword"
