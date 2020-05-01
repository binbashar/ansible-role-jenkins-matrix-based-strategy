# Binbash - Ansible Role: Jenkins Matrix-based Strategy

Ansible role for enabling and configuring Jenkins Matrix-based Strategy.

## Requirements
* Jenkins with Matrix-based Strategy plugin installed

## Examples
```
  - role: binbash_inc.jenkins-matrix-based-strategy
    jenkins_pbms_users:
    - name: your-user
      permissions:
      - hudson.model.Hudson.READ
      - hudson.model.Hudson.ADMINISTER
```
