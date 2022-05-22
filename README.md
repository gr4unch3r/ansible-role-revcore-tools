# Ansible RevCore Tools Role

[![CI](https://github.com/gr4unch3r/ansible-role-revcore-tools/actions/workflows/ci.yml/badge.svg)](https://github.com/gr4unch3r/ansible-role-revcore-tools/actions/workflows/ci.yml)

Ansible role to provision [SentinelLabs RevCore Tools](https://github.com/SentineLabs/SentinelLabs_RevCore_Tools) for a Windows-based reverse engineering/malware analysis environment.

## Requirements

- Clean Windows 10 VM configured for remoting with Ansible ([Guide](https://docs.ansible.com/ansible/latest/user_guide/windows_setup.html))
- [ansible.windows](https://galaxy.ansible.com/ansible/windows)
- [community.windows](https://galaxy.ansible.com/community/windows)
- [chocolatey.chocolatey](https://galaxy.ansible.com/chocolatey/chocolatey)

## Example Playbook

```
- hosts: all
  roles:
    - gr4unch3r.revcore_tools
```

## License

MIT

## Author Information

gr4unch3r [at] protonmail [dot] com
