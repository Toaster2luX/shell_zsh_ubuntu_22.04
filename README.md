# [Ansible] Installation et personnalisation de zsh sous (x)Ubuntu 20.04 / 22.04


Installation du shell zsh, framework oh-my-zsh, thème powerlevel9k, pluguns zsh-syntax-highlighting et zsh-autosuggestions, personnalisation du .zshrc


## Exécution

```bash
$ ansible-playbook -i inventories playbooks/playbook.yml
```

## Exécution avec un tag

```bash
$ ansible-playbook -i inventories playbooks/playbook.yml --tags "deb"
```

## Structure

```bash
.
├── inventories
│   └── hosts
├── playbooks
│   └── playbook.yml
├── README.md
└── role_zsh
    ├── defaults
    │   └── main.yml
    └── tasks
        ├── change_shell.yml
        ├── install_zsh.yml
        └── main.yml
```


## Source

[Shell zsh ubuntu 22.04](https://it.izero.fr/ansible-installation-et-personnalisation-de-zsh-sur-xubuntu-20-04/)

## License

[MIT](https://choosealicense.com/licenses/mit/)

