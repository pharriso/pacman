rhel_multi_instances
=========

creates one or more rhel instances

Role Variables
--------------

The following variables can be overriden.

| Name                    | Default value         |                                                                                  |
|-------------------------|-----------------------|----------------------------------------------------------------------------------|
| ec2_region              |                       | EC2 region                                                                       |
| os                      | rhel8                 | os type                                                                          |
| keypair                 |                       | SSH Keypair name                                                                 |
| ami_id                  |                       | AMI ID                                                                           |
| security_group          |                       | Secuirty group name                                                              |
| instance_tags           | webserver             | Instance tags                                                                    |
| count_tag               | webserver             | Tag to use to check desired count                                                |
| instance_count          | 1                     | Number of instances                                                              |
| check_port              | 22                    | Port to poll to check instance                                                   |

Author Information
------------------

Pat Harrison
