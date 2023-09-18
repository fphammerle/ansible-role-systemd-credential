# Ansible Role: Systemd Credential

Ansible role for storing secrets in systemd's [credential store](https://systemd.io/CREDENTIALS/).

## Required Input Variables

```yaml
systemd_credential_name: some-password
systemd_credential_content: secret password
```
