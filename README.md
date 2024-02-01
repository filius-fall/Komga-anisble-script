""" ansible-playbook -i inventory.ini -e @config_paths.yml -e @owners.yml deploy_komga.yml """

example for 

inventory.ini

`
    <ip-address> ansible_user=<your_username> ansible_ssh_private_key_file=<if you have key add here like (~/.ssh/rpi_new/id_rsa)>
`

config_paths.yml

`
    komga_config_path: "/path/to/config"
    komga_data_path: "/path/to/data"
    komga_main_path: "/path/to/komga_file"

`

owners.yml
`
    username: <username>
    groupname: <group>

`

