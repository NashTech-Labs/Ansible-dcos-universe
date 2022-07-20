### What will this role do ?

The above dcos universe role will help you install local dcos universe from your own dcos tar file in your system and the machines on which you will run the role.

This role will further run local dcos universe as service and local dcos registry as a service in the particular machine.



#### Variable used in the role.

- artifacts_s3_bucket: ' Your bucket in which you will keep the local dcos universe tar file.'

- s3_endpoint: - 's3.amazonaws.com'

#### Prerequisite

- Docker should be installed in the system on which this playbook will run.

### How to run the playbook .

To run the playbook follow the below command:-

`ansible-playbook -i <your inventory file> playbook.yml`

**Note**:-  If you are running on your local system then you don't need to pass inventory file. Just use localhost in hosts of playbook. 