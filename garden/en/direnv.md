---
category: tools
tags:
  - devops
---
Great for working on multiple projects/organizations on one cloud. Great for using terraform. I use it to provide needed secrets and switch project automatically. Secrets could be acheived by tfvars or something, but project switching can't (because of credentials).

My setup is: project dir with .envrc file where i have env vars pointing to credential directory and separate dir per repository in such project. It makes my direnv providing env vars for one project. 