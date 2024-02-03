# Ansible Server Information Playbook

This Ansible playbook is designed to gather information about ports in use, firewall configurations, users, root users, and other relevant data on target servers.

## Usage

1. Ensure Ansible is installed on your control node.

2. Clone this repository to your local machine:
     ...

       git clone https://github.com/CHARANPRAJWAL/SERVER-INFO-ANSIBLE.git

     ...

3. Edit src (file to copy) and dest (your local destinaton) path for the last task (Copy output.txt file from server to local machine). 

3. Edit the `inventory` file to specify the target servers.

4. Run the playbook:

    ```
    ansible-playbook -i inventory Server-Details-PB.yml

    ```
5. Verfiy the output.txt file created on both Src and Dest paths.
