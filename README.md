
## JupyterHub for co op lab education  Thankyou jupyterhub/the-littlest-jupyterhub

JupyterHub brings the power of notebooks to groups of users. It gives users access to computational environments and resources without burdening the users with installation and maintenance tasks.


## Acknowledgements

 - [Thank you guide (tljh.jupyter.org)](https://tljh.jupyter.org/en/latest/contributing/dev-setup.html)
 - [Jupyterhub](https://jupyter.org/hub)
 - [Docker](https://docs.docker.com/)


## installation

Use command to create container

```bash
  docker compose up -d
```

Remote to container docker

```bash
  docker exec -it tljh-dev /bin/bash
```

use this command to create admin default user is admind:password

```bash
  python3 /srv/src/bootstrap/bootstrap.py --admin admin:password
```

## INFO

#### How do I open Jupyterhub? 

```bash
  localhost:12000
```

#### What default admin user password ?

password

#### What python version ?

python 3.10


Enjoy =w=
