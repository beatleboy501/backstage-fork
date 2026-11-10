---
'@backstage/plugin-kubernetes-backend': patch
---

The Kubernetes proxy now returns a conflict error when more than one configured cluster has the requested name, instead of silently routing the request to the first match. Give each cluster a unique name to target it through the proxy.
