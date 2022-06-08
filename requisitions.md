# MongoDB + C#

## Requisitos

1. Visual Studio 2022
2. Docker (para rodar o MongoDB)
3. MongoDb Compass

## MongoDB no Docker
```
docker pull mongo
```
### Instalação MongoDB
```
docker run -v ~/docker --name mongocsharp -d -p 27017:27017 -e MONGO_INITDB_ROOT_USERNAME=expertostech -e MONGO_INITDB_ROOT_PASSWORD=mongo123 mongo
```

### Instalar SGBD MongoDB Compass
<https://www.mongodb.com/pt-br/products/compass>

## Criando Projeto no Visual Studio 2022

Crie um projeto MVC no Visual Studio 2022
Instale o Driver do MongoDB Clicando com o botão direito em cima do projeto e indo em <strong>"Gerenciar pacotes do NuGet" </strong>
e pesquise por MongoDB.Driver e intale.



