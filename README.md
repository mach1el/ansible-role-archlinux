# ansible-role-archlinux
Auto building,config my arch linux

## Role pathes

	├── defaults
	│   └── main.yml
	├── handlers
	├── tasks
	│   ├── main.yml
	│   ├── setup_fonts.yml
	│   ├── setup_globalmenu.yml
	│   ├── setup_openbox.yml
	│   ├── setup_themes.yml
	│   └── setup_yay.yml
	└── templates

## Role Playbook
	---
	- name: Building archlinux for local server
	  hosts: local_asterisk

	  roles:
	  	- '../ansible-role-archlinux'