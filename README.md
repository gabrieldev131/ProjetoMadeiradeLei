# Tutorial de uso

## rodar o backend
    mvn spring-boot:run

## Url de acesso ao backend
    http://localhost:8080/swagger-ui/index.html

## usuario e senha admin
    usuario: admin@madeiradelei.com
    senha: Admin@123

## login swagger
    coloque o token jwt que aparece ao dar login

## acesso ao banco de dados
    Em src/main/resources/application.properties:
        
        spring.application.name=sistemaprincipal
        spring.mongodb.uri=mongodb+srv://<usuario>:<senha>@madeira.xkydx8a.mongodb.net/?appName=madeira 
        spring.mongodb.database=madeira
        api.security.token.secret=minha_chave_secreta_muito_forte_12345


## Front

    