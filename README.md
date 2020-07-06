# ansible-role-archlinux
![Version](https://img.shields.io/github/v/release/mach1el/ansible-role-postgresql?color=brown&style=plastic) ![License](https://img.shields.io/github/license/mach1el/ansible-role-postgresql?color=purple&style=plastic)
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