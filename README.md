# Projeto Deploy Django

### Criando build Docker
- docker-compose up --build

### Apagar container
- docker ps -a (Ver containers)
- docker rm IDCONTAINER (Excluir container)

### Apagar imagens
- docker image ls (Ver Imagens)
- docker rmi IDIMAGEM (Excluir imagem)

### Criando app dentro do container
- docker-compose run djangoapp python manage.py startapp nomeapp