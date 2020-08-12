# Ansible-Lecter-Apache-Install-Uninstall-Simple

### Simple way to install, enable, open the firewall for Apache servers and undo all

For RedHat systems only folks, yum yum. But it can easily be modified for other distros. Anyway there are two files, install.yml installs, enables, and opens the firewall for Apache while uninstall undos all three of those steps. 

# Example Run 1
```sh
$ ansible-playbook install_apache.yml 
```
# Example Run 2
```sh
$ ansible-playbook uninstall_apache.yml 
```

### Tech and Running the file

These are very simple plays Boo, they're not Shakespeare. 