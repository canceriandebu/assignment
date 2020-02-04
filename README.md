# Thoughtworks
-------------------------------------------------------------------------------
## Edit the parameter in files before running the playbook

file name: aws_keys.yml\
Enter your aws_access_key and aws_secret_key

-------------------------------------------------------------------------------

file name: hosts\
Enter the path for ansible_ssh_private_key_file under [uiservers:vars] and [backendservers:vars]

-------------------------------------------------------------------------------

To deploy static file with provision of UI Server\
file name: aws_provisiong_ui.yml
- key_name:
- instance_type:
- image:
- vpc_subnet_id:
- group_id:
- region:

### Run the playbook as "ansible-playbook -i hosts aws_provisioning_ui.yml"

-------------------------------------------------------------------------------

To deploy static file with provision of UI Server\
file name: aws_provisiong_backend.yml
- key_name:
- instance_type:
- image:
- vpc_subnet_id:
- group_id:
- region:

### Run the playbook as "ansible-playbook -i hosts aws_provisioning_backend.yml"
