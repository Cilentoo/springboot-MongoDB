# Workshop MongoDb
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/devsuperior/sds1-wmazoni/blob/master/LICENSE) 

# Sobre o projeto
Workshop que usa o modelo do banco de dados MongoDb, onde o objetivo era montar um modelo de site de postagens, onde os usuários são relacionados a postagens,
e essas postagens por sua vez tem comentários de outros usuários associados, na prática como funciona um facebook, tudo isso usando springtool e relacionado ao MongoDb.

Workshop that uses the MongoDb database model, where the objective was to set up a post website model, where users are related to posts,
and these posts in turn have comments from other associated users, in practice how Facebook works, all using springtool and related to MongoDb.

## Table User (MongoCompass)
![User](https://github.com/Cilentoo/springboot-MongoDB/blob/main/assets/Tabela-Usuario.png)

## Table Post (MongoCompass)
![Post](https://github.com/Cilentoo/springboot-MongoDB/blob/main/assets/tabela-post.png)

## Modelo de Comunicação
![Modelo de Comunicação](https://github.com/Cilentoo/springboot-MongoDB/blob/main/assets/Modelo-de-comunicacao.png)

## Modelo de Entidades
![Modelo de Entidades](https://github.com/Cilentoo/springboot-MongoDB/blob/main/assets/modelo-de-entidades.png)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
- MongoDB
## Implantação em produção
- Banco de dados: MongoDbCompass

# Como executar o projeto

## Back end
Pré-requisitos: Java 17

```bash
# clonar repositório
git clone https://github.com/Cilentoo/springboot-MongoDB.git

# executar o projeto
./mvnw spring-boot:run
```
