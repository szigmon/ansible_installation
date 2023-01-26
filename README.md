# ansible_installation
Ansible Installation Error


The Following Error may occur while installing Ansible Automation Platform:

TASK [ansible.automation_platform_installer.preflight : Fail if the filesystem is mounted with noexec] ***
failed: [aap.example.com] (item={'changed': True, 'found': 1, 'msg': '1 line(s) removed', 'backup': '', 'diff': [{'before': '', 'after': '', 'before_header': '/proc/mounts (content)', 'after_header': '/proc/mounts (content)'}, {'before_header': '/proc/mounts (file attributes)', 'after_header': '/proc/mounts (file attributes)'}], 'invocation': {'module_args': {'name': '/proc/mounts', 'regexp': ' /var .*noexec', 'state': 'absent', 'path': '/proc/mounts',
