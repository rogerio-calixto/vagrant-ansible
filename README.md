# vagrant
Creates VM with Ubuntu/Nginx

## Note:

Vagrant relies on interactions with 3rd party systems, known as
"providers", to provide Vagrant with resources to run development
environments. Examples are VirtualBox, VMware, Hyper-V.

# some vangrant commands

- vagrant init -> (Creates Vagrantfile template)
    - ex: vagrant init ubuntu/focal64

- vagrant up      -> creates vm
- vagrant ssh     -> connects to vm
- vagrant reload  -> updates vm
- vagrant destroy -> destroy vm

# Test

After connect to vm, open browse and access: http://localhost:8080/
