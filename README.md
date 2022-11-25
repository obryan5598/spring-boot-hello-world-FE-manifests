# spring-boot-hello-world-FE-manifests

Once OpenShift GitOps is setup, the following role should be added:
```
oc adm policy add-role-to-user admin system:serviceaccount:openshift-gitops:openshift-gitops-argocd-application-controller -n <project>
```
