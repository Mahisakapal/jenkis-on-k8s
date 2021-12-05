# jenkis-on-k8s
## create a deplyment and sservice using this mainifast
## than access jenkins secret key 
'kubectl exec  -n jenkins jenkins-655f99d864-kpfs5 -- /bin/bash -c "cat /var/jenkins_home/secrets/initialAdminPassword"'
'kubectl exec  -n <nmespase> <pod> -- /bin/bash -c "cat /var/jenkins_home/secrets/initialAdminPassword"'
 after this go and access you jenkin on nodeIP:32000 and install plugin 
  ![image](https://www.jenkins.io/doc/book/resources/scaling-jenkins-on-kubernetes/kubernetes-plugin-configuration.png)


