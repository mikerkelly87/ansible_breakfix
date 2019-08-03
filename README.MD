Ansible Breakfix 
   
Setup Steps:  
1) Create an `Ubuntu 18.04` server using your preferred Hypervisor or Cloud Provider  
2) Create the user `rack` and make sure the user can run commands as `sudo`  
3) Clone this repo into `/home/rack`  
  
Desired Results:  
1) Run the command `ansible-playbook /home/rack/ansible_breakfix/playbooks/wordpress_ansible.yml`  
2) Connecting to the IP of your server in your web browser (`http://<YOUR_SERVER_IP>`) should result in viewing the Wordpress installation screen
3) Take notes to present on all the steps you had to take with a brief description as to why you did it as there may be multiple ways to resolve certain issues  
  
Once you see the Wordpress welcome screen prompting you for the `Site Title`, `Username`, `Password`, and `Email` you have resolved all the issues  
  
None of the issues should be resolved by manually fixing things on the server. All issues must be resolved in the Ansible playbooks and templates  
  
If the playbook output gives an error followed by `...ignoring` you can ignore it, but all other playbook errors must be resolved