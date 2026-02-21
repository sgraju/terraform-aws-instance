# AWS EC2 Instance

Thi module creates EC2 instance.

### Inputs

* ami_id - (Optional) Defaults to ``` ami-0220d79f3f480ecf5 ```
* instance_type - (Required) User must supply instance type either t2.micro or t3.small or medium
* sg_ids - (Required) user must supplu security group Ids to attache EC2 instance
* tags

### Outputs

* public_ip - Public IP of the instance created
* private_ip - Private IP of the instance created