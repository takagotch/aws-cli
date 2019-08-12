### aws-cli
---
https://github.com/aws/aws-cli

```
[default]
aws_access_key_id=<default access key>
aws_secret_access_key=<default secret key>
region=us-west-1

[profile testing]
aws_access_key_id=<testing access key>
aws_secret_access_key=<testing secret key>
region=us-west-2

[default]
aws_access_key_id=<default access key>
aws_secret_access_key=<default secret key>
region=us-west-1
```

```sh
aws iam list-users
aws ec2 authorie-security-group-ingress --group-name MySecurityGroup \
aws ec2 authorize-security-group-ingress --group-name MySecurityGroup \
  --ip-permissions http://mybucket.s3.amazonaws.com/ip_perms.json
aws iam list-users --query Users[].UserName
aws s3api list-objects --bucket b --query Contents[].[Key,Size]
aws ec2 describe-instances --query \
  'Reservations[].Instances[].[InstanceId,State.Name,Tags[?Key==`Name`] | [0].Value]'
pip install awscli
sudo pip install awscli
pip install --user awscli
pip install -upgrade awscli
sudo pip install awscli --ignore-installed six

export AWS_CONFIG_FILE=/path/to/config_file
export AWS_DEFAULT_REGION=us-west-2
export AWS_PROFILE=testing
```

```
```


