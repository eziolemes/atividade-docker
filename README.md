# atividade-docker

## Criar a pasta node_modules
npm i express body-parser nodemon mongoose

## Executar a aplicação
sudo docker-compose up

## endpoits
insert: post http://localhost:9000/api/carros/novo/
        json = {"marca":"ferrari", "modelo":"812" }

edit: put http://localhost:9000/api/carros/editar/:id
        json json = {id: 1,"marca":"ferrari", "modelo":"812" }

find: get http://localhost:9000/api/carros/

delete: put http://localhost:9000/api/carros/delete/:id