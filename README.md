 <h1 align="center">
    project-back-end
</h1>
<p align="center">
    <img src="https://img.shields.io/badge/Java-SpringBoot-black">
</p>

Tasks (To-Do List). 

## Tecnologias

- [Spring Boot](https://spring.io/projects/spring-boot)
- [Spring MVC](https://docs.spring.io/spring-framework/reference/web/webmvc.html)
- [Spring Data JPA](https://spring.io/projects/spring-data-jpa)
- [Mysql](https://dev.mysql.com/downloads/)
- [Docker](https://www.docker.com/get-started/)

## Práticas adotadas

- SOLID,
- API REST
- Consultas com Spring Data JPA
- Injeção de Dependências
- Tratamento de respostas de erro

## Como executar

### Localmente
- Clonar o respositório git
```
TODO
```
- Acessar diretorio
```
cd project-back-end
```
- Construir o projeto:
```
./mvnw clean package
```
- Executar:
```
java -jar target/todo-list-0.0.1-SNAPSHOT.jar
```

### Utilizando Docker

Você também pode executar o projeto com Docker, incluindo um contêiner MySQL. Certifique-se de que o Docker esteja instalado no seu sistema. 
Siga os passos abaixo:
1. Execute o seguinte comando para criar um contêiner MySQL:
```
docker run --name mydatabase -e MYSQL_ROOT_PASSWORD=my-secret-pw -d mysql
```
## API Endpoints

Foi utilizado o [Postman](https://www.postman.com/) para realizar as requisições HTTP
