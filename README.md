# shark
Arquivos de uma aplicação NODEJS no ubuntu 20.04 com docker

Para buildar a partir deste código, basta clonar para sua máquina:

 git clone https://github.com/celosop/shark.git

Assim que clonar, usar um cd para entrar na pasta criada, neste caso, shark. Depois usar o seguinte comando:

 docker build -t nomeuserdockerhub/nomerepodockerhub:tag .
 
Depois só conferir a imagem criada com o comando:

 docker images
 
Para levantar o serviço basta usar o Docker run:

 docker run -ti --name nomeimagem -p 80:8080 -d nomeuserdockerhub/nomerepodockerhub:tag
 
 
Criar nova BRANCH no github:

git checkout -b MinhaNovaBrach

Depois, quando quiser subir a branch, faça os commits:

git commit -m 'Comentário do commit da minha nova branch'

Depois, subindo de fato:

git push --set-upstream origin MinhaNovaBrach
