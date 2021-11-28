To install ansible on Ubuntu:
	sudo apt-get install ansible


To Run the playbook against the inventory file that you created
	ansible-playbook <ansible_playbook.yaml> -i <path_to_inventory_file>

To Run the playbook with the tags 
	ansible-playbook <ansible_playbook.yaml> -i <path_to_inventory_file> -t <your_tag_in_playbook>	

To Run the playbook in the interactive mode
	ansible-playbook <ansible_playbook.yaml> -i <path_to_inventory_file> --step

To list the tags that are available in the palybook
	ansible-playbook <ansible_playbook.yaml> --list-tags

To skip the tags
	ansible-playbook <ansible_playbook.yaml> -i <path_to_inventory_file> --skip-tags <tag_1>,<some_other_tag>

