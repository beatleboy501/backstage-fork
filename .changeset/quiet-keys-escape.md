---
'@backstage/plugin-scaffolder-react': patch
---

Fixed the scaffolder review step so that fields whose names contain a `/` are masked, hidden and labelled using their own title, the same as any other field. Previously a password or secret field with such a name could be shown in plain text.
