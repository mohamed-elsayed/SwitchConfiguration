# switch Configuration

This project to mainly ease the process of switch configuration.
You can use this playbook to configure switch based on configuration variable file.
You can create a VLAN, Interface VLAN with the corresponding IP, and assign the required interfaces to that VLAN.

## Usage
Edit the configuration file to represent your desired final stage:
```vim
vim vars/configurationFile
```
Run Ansible playbook:
```ansible
ansible-playbook BSG.yaml
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)