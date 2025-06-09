# n8n workflow
n8n: An Open-Source Low-Code/No-Code Workflow Automation Tool.

### Install Docker and n8n via Docker
1- Use the link below and install Docker based on your ios:[https://docs.docker.com/get-started/get-docker/](https://docs.docker.com/get-started/get-docker/)
2- Open a terminal and test your docker installation: <br>
 ``` bash
docker run hello-world
docker –version
```
### Docker install n8n 
Free installation of n8n on your machine, via docker using the link provided [https://docs.n8n.io/hosting/installation/docker/](https://docs.n8n.io/hosting/installation/docker/)
The best is to use the commands below. So, although n8n is on docker, Ollama running on the machine can be recognizable: <br>
```bash
docker volume create n8n_data

docker run -it --rm \
  --name n8n \
  --add-host=host.docker.internal:host-gateway \
  -p 5678:5678 \
  -v ~/.n8n:/home/node/.n8n \
  n8nio/n8n
```
### 



