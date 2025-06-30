# inicializador-de-servicos-docker
Repositório com comando para rodar o serviço Portainer (ferramenta de gerenciamento Docker) usando Docker

# Rodar Portainer com Docker

Para rodar o Portainer, execute o comando:

bash
docker run -d -p 9090:9000 --name portainer1 -v /var/run/docker.sock:/var/run/docker.sock portainer/portainer-ce

Portainer é uma interface gráfica (GUI) que facilita o gerenciamento de ambientes Docker e Kubernetes.
Com ele, você pode criar, visualizar e controlar containers, imagens, volumes e redes de forma simples pelo navegador, sem usar só linha de comando
