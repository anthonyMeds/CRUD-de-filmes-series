# Resumo

O ScreenMatch é uma aplicação CRUD (Create, Read, Update, Delete) desenvolvida em Java utilizando as seguintes tecnologias: JPA, Spring e Thymeleaf. A aplicação permite cadastrar, atualizar, listar e deletar filmes.


## Tecnologias Utilizadas
- JPA (Java Persistence API)
- Spring Framework
- Thymeleaf

## Instruções de Instalação

1. Certifique-se de ter o Java Development Kit (JDK) instalado na sua máquina.
2. Clone o repositório do projeto para a sua máquina local.
3. Abra um terminal ou prompt de comando e navegue até a pasta do projeto.
4. Execute o seguinte comando para compilar o projeto:

   ```shell
   javac *.java

  java Principal

  Acesse: http://localhost:8080/filmes
  
Obs. Configuração do banco de dados (Configure no application.properties):
spring.datasource.url=jdbc:mysql://localhost/screenmatch?createDatabaseIfNotExist=true
spring.datasource.username=root
spring.datasource.password=root

  
