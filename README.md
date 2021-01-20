# Blade_Fury

This is just a copy from the internet, but ill keep this here so that i can come back to it when i need it.

#### Create vagrant machine:
```vagrant up```

#### Run ansible.yml against the machine *(and create the nessesary things to run manually also)*:
```vagrant provision```

#### Run manually:
```ansible-playbook --private-key=~/.vagrant.d/insecure_private_key -u vagrant -i .vagrant/provisioners/ansible/inventory/vagrant_ansible_inventory playbook.yml```


Now you simply write whatever code in the **ansible.yml** you like. And ofc test it against the vagrant machine you just created.
