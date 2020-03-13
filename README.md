# curso-master-devops
Projetos do curos Master Devops With Docker, Kunbenetes....

DOCKER DICAS e Observações

docker --help

docker rmi <id>

docker stop <id>

No comando "docker run -p 5000:5000 in28min/hello-world-nodejs:0.0.1.RELEASE"
A parte do comando -p 5000:5000 permite que a porta 5000 no container seja escutada
na porta 5000 da máquina local.

docker run -d -p 5000:5000 in28min/hello-world-nodejs:0.0.1.RELEASE - O -d permite iniciar o container em mode detach. 
a console não fica presa

docker images               -> lista as imagens que foram baixadas

docker container ls         -> lista os containeres que estão executando.

docker container ls -a      -> lista todos os containeres incluindo aqueles que foram parados.

docker container stop <id>  -> para a execução de um container.
docker container kill <id>  -> para o container imediatamente (sem shutdown)

docker container pause <id>   -> pausa um container
docker container uppause <id> -> retirar a pausa do container

docker container inspect <id> -> exibe informações sobre o container

docker container prune > remove todos os containers

docker pull            -> faz o download da imagem.

docker search <ex.>    -> Faz uma busca no hub para procurar imagens com a tag (ex) utilizada.

docker history <image name:tag ou ID> -> lista o histórico da imagem.

docker image inspect <ID> -> lista uma serie de informações sobre a imagem.

docker image remove <id ou name:tag> -> remove uma imagem.





