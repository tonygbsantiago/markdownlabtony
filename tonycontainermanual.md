# Manual do Container de Tony
## Tony Gabriel Bento Santiago

Comandos para utilizar:

- docker ps --> (Para listar os containers criados e com isso certificar-se que o nome que deseja utilizar já não está em uso!)
- docker run -d -p 61030:61030 -it --rm  --name  tonytcpserver -v "$PWD":/var/www/servidortcp -w /var/www/servidortcp python:2 python ./serv_sock.py --> (Para criar o container e iniciar o arquivo serv_sock.py que está inserido nele!)
- docker ps --> (Para listar novamente os containers e verificar se o seu foi criado!)