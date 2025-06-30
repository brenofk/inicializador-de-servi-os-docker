# inicializador-de-servicos-docker
Repositório com comando para rodar o serviço Portainer (ferramenta de gerenciamento Docker) usando Docker

# Rodar Portainer com Docker

Para rodar o Portainer, execute o comando:

bash
docker run -d -p 9090:9000 --name portainer1 -v /var/run/docker.sock:/var/run/docker.sock portainer/portainer-ce


