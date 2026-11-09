---
'@backstage/plugin-scaffolder-backend-module-confluence-to-markdown': patch
---

Fixed a file descriptor leak when downloading Confluence attachments, and a case where a failed download could leave the scaffolder step hanging instead of reporting the error.
