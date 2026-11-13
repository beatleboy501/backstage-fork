---
'@backstage/plugin-scaffolder-backend-module-gitlab': patch
---

The `gitlab:group:ensureExists` action no longer fails when the path starts with an existing personal GitLab user namespace. The namespace is reused instead of attempting to create a group with the same name. Requesting subgroups under a personal namespace now fails with a clear error.
