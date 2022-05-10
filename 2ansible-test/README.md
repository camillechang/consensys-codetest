##### 1 Create an AWS EC2 instance via Ansible static inventory

1. See file create_ec2.yml
2. Preconditions:
   create an keypair with name ansiblekeypair in AWS IAM.
3. This will create an ec2 instance from amazon linux2 with name dev-besu-\* in region
4. Use the following command:
   `ansible-playbook create_ec2.yml`
