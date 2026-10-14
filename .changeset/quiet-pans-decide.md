---
'@backstage/plugin-scaffolder-backend': patch
---

Fixes a regression where scaffolder step values consisting of a singular template statement block (ex. `if: "{% if parameters.foo == 'bar' %}true{% else %}false{% endif %}"`), were rendered as the strings `"true"` and `"false"` instead of their boolean values. This caused steps with `if` conditions to always run.
