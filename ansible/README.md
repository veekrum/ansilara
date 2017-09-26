# How to use it
0. You must have ansible installed locally.
1. Clone the repository locally.
2. Change the ip's in the hosts directory files.
3. Change the group_vars settings.
4. Check the vars folder settings in order to make sure that you are ok with the defaulted settings.
5. Run the playbook on the desired host:
    - ansible-playbook -i ansible/hosts/staging playbook.yml
    - ansible-playbook -i ansible/hosts/production playbook.yml

# What to expect
This playbook will install all the needed elements for a Laravel 5.x application. 

- NGINX
- PHP
- MYSQL
- PYTHON

# Notes
The nginx defaults to the 80 port (a.k.a http), I intend to add a block for https in the future.
As a side note I will say that this works really well in conjunction with the deploy script: [envoy-deployscript](https://github.com/nickfan/envoy-deployscript)

# Credits
This playbook is based on multiple roles. All the credit for those go to their creators.

