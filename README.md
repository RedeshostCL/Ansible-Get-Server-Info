# Ansible Get Server Information

:es: Este proyecto tiene como propósito adquirir información base de un(os) servidor(es) Linux y retornar dicha información en formato markdown.

:us: This project aims to acquire the base information of a Linux server(s) and retrieve this information in a markdown format.

## Usage

:es: Para correr este proyecto, ejecuta el siguiente comando, donde *'user'* es igual al usuario remoto:

```bash
$ ansible-playbook -i inventory main.yml -uuser --ask-pass
```

:us: To run this project, execute the following command, where *'user'* is the remote user:

```bash
$ ansible-playbook -i inventory main.yml -uuser --ask-pass
```