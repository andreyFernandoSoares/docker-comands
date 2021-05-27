# docker-comands
Docker Commands


docker run {image-name} (Baixa e roda uma imagem)

docker ps (Lista containers ativos)

docker ps -a (Lista todos containers)

docker run -it {image-name} (Interage diretamente com o terminal da imagem)

docker start {id-container} (Starta container ja baixado)
  
docker stop {id-container} (Para container que esta sendo executado)

docker start -a -i {id-container} (Starta container ja baixado e Interage diretamente com o terminal da imagem)

docker rm {id-container} (Remove container especificado)

docker container prune (Remove todos containers)

docker images (Montra todas suas imagens)

docker rmi {image-name} (Remove imagem especifica)

docker stop -t {seconds} (Remove apos tantos segundos o default é 10 segundos)

docker run -d -P {image-name} (Roda uma imagem desacoplada do terminal e em uma porta aleatoria)

docker port {id-container} (Mostra as portas externas referentes as portas internas do container)

docker machine ip (Mostra o ip da sua maquina virtual)

docker run --name {container-name} {image-name} (Atrela um nome de container para sua imagem)

docker run -d -p {external-port}:{internal-port} {image-name} (Roda uma imagem descoplada do terminal e indique as referencias de portas internas e externas)
