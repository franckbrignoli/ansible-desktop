## Usage
    $ sudo apt-get install software-properties-common
    $ sudo apt-add-repository ppa:ansible/ansible
    $ sudo apt-get update
    $ sudo apt-get install ansible
    
    $ sudo cp hosts /etc/ansible/hosts 

    $ ansible-playbook -s main.yml --ask-sudo-pass

## TODO

- [ ] Remove hardcoded docker ppa
- [ ] Custom keyboard shortcuts
- [ ] Set up ZSH 
- [ ] Git global vars

...
