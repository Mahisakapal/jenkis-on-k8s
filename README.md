# jenkis-on-k8s
## create a deplyment and sservice using this mainifast
## than access jenkins secret key 
'kubectl exec  -n jenkins jenkins-655f99d864-kpfs5 -- /bin/bash -c "cat /var/jenkins_home/secrets/initialAdminPassword"'
'kubectl exec  -n <nmespase> <pod> -- /bin/bash -c "cat /var/jenkins_home/secrets/initialAdminPassword"'
 after this go and access you jenkin on nodeIP:32000 and install plugin 
  ![image](https://user-images.githubusercontent.com/25150324/144749153-bbd5a4fc-f31f-40f3-b8d5-66b0b084d5a8.png)

![image](https://user-images.githubusercontent.com/25150324/144749169-6e48f29c-0b6c-43a7-a85f-b88ab42c5f77.png)
