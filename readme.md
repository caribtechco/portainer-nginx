## Portainer and Nginx Proxy Manager Docker Stack Deployment Files

Easily deploy, configure and secure containers in minutes on Docker, Kubernetes, Swarm and Nomad in any cloud, datacenter or device using Portainer.


## Deployment

The following services will be initiated once deployed:

- Portainer CE
- Portainer Agent
- MariaDB
- Nginx Proxy Manager


#### Deploy using Docker Stack / Swarm
```bash
bash portrun.sh
```

#### Deploy using Docker Compose
```bash
docker-compose up -d
```


##  What's Portainer?
Portainer's intuitive UI and codified best practices helps organizations to adopt containers quickly and efficiently.

- Reduce the operational complexity associated with multi-cluster management
- Bridge the skills gap and facilitate feature discovery and learning with an intuitive UI
- Codify cloud-native best practices with design templates and default configurations
- Consistently apply and centrally manage access, permissions and activity logging 

Portainer's multi-cluster, multi-cloud container management platform supports Docker, Swarm, Nomad, and Kubernetes running in any Data Center, Cloud, Network Edge or IIoT Device. 

See [Portainer Documentation](https://www.portainer.io/) for more details.


## What's Nginx Proxy Manager?
This project comes as a pre-built docker image that enables you to easily forward to your websites running at home or otherwise, including free SSL, without having to know too much about Nginx or Letsencrypt.

See [Nginx Proxy Manager Documentation](https://nginxproxymanager.com/guide/) for more information.