Working through this
Currently unsure how the namespace binding works, by default these placements are not creating the namespace binding

openshift gitops on ACM was not managing those clusters depsite cluster placement 

reused previous name of nwg-z and it worked unsure what object was missing or not binding :( 


Cert manager seems to complain about crds not being present on install 

lots of failures due to argo permissions over ns 
oc adm policy add-role-to-user admin system:serviceaccount:openshift-gitops:openshift-gitops-argocd-application-controller -n <namespace>

TODO
Gitops is not deployed on the cluster ocpz1 ocpz2 (added)
GitOps install is ugly mess of dependancies 


