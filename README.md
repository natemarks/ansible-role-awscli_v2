# awscli_v2
=========

Use the AWS cli v2 installer to manage the aws client installed at the default,
system-wide location. On linux, this is a symlink at /usr/local/bin/aws to the
/usr/local/aws-cli install location

https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2-linux.html#cliv2-linux-install


## Usage
----------------

```shell
git clone https://github.com/natemarks/ansible-role-awscli_v2.git
cd ansible-role-awscli_v2
sudo apt install -y curl 
bash -c 'curl "https://raw.githubusercontent.com/natemarks/pipeline-scripts/v0.0.31/scripts/run_playbook.sh" | bash -s --  -p  playbook' 
```
