
When both app1 and app2 are having same sources and resources , argocd will put both the apps on outofsync state due to the shared resource 
even if app1 is created before the app2 


# FailedOnSharedResource=true
when this option is used this is app2 will stay in out of sync state as the resource is already been created on app1 