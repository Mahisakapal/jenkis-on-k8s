# jenkis-on-k8s
## create a deplyment and sservice using this mainifast
## than access jenkins secret key 
'kubectl exec  -n jenkins jenkins-655f99d864-kpfs5 -- /bin/bash -c "cat /var/jenkins_home/secrets/initialAdminPassword"'
'kubectl exec  -n <nmespase> <pod> -- /bin/bash -c "cat /var/jenkins_home/secrets/initialAdminPassword"'
 after this go and access you jenkin on nodeIP:32000 and install plugin 



https://www.jenkins.io/doc/book/scaling/scaling-jenkins-on-kubernetes/
 https://www.blazemeter.com/blog/how-to-setup-scalable-jenkins-on-top-of-a-kubernetes-cluster
 https://www.youtube.com/watch?v=DAe2Md9sGNA
 https://www.youtube.com/watch?v=DAe2Md9sGNA
 https://www.youtube.com/watch?v=laAAzdw11dA
