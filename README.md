# awscli_v2
=========

Use the AWS cli v2 installer to manage the aws client installed at the default,
system-wide location. On linux, this is a symlink at /usr/local/bin/aws to the
/usr/local/aws-cli install location

https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2-linux.html#cliv2-linux-install


## Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
```yaml
---
- name: Run awscli_v2
  hosts: localhost
  roles:
    - natemarks.awscli_v2
```
