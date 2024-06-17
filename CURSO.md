# Java Spring Boot 3

## Project Metadata do Spring Initializr

Em **Group**, geralmente é utilziado o domínio de forma reversa, exemplo:
google.com ficaria com.google.

Em **Artifact** e **Name** utilizamos o nome do projeto em sí, no exemplo criado foi utilizado o Artifact e Name como sendo runnerz.

Em **Description** temos a descrição do projeto.

Em **Package name** temos o nome do pacote principal do projeto. Geralmente é composto pelo **Group** + **Artifact**.

## Dependencies do Spring Initializr

Dependencies basicamente permite adicionar pacotes que possuem diversas funcionalidades. Como Spring Web, Spring Security, Spring Boot DevTools, Lombok, MySQL Driver, etc...


## Pom.xml

O arquivo **pom.xml** é onde todas as nossas dependências e informações a respeito do nosso projeto são armazenados.

## Classe Principal

A classe principal é responsável por executar o nosso projeto por completo, é onde todo o nosso código roda. A classe principal possui uma anotação chamada SpringBootApplication que indica que a classe é a porta de entrada do nosso projeto.

## Usando o Maven para rodar a nossa aplicação

Para ordar a nossa aplicação basta abrir o terminal na raiz do projeto e digitar
```java
./mvnw spring-boot:run
```

## O que é uma Bean?

Uma bean é basicamente a instância de uma classe, ou seja, é um container de objetos que possui diversas informações.


## Estruturação de um projeto Spring

Há duas formas comuns de estruturar nossos projetos com Spring Boot, uma delas é com a arquitetura de camadas(layers) que podem ser representadas pelo padrão de arquitetura MVC, onde teremos repositórios como repository, controller, view, services, model etc...

Outra forma interessante de estruturar nosso código é utilizando um padrão de arquitetura chamado Package By Feature, que basicamente representa um ou N pacotes, onde cada pacote possui todas as classes necessárias para aquela feature em específico.

Recomendo a leitura do artigo [Package by Layer vs Package by Feature
](https://medium.com/sahibinden-technology/package-by-layer-vs-package-by-feature-7e89cde2ae3a)


[Voltar](README.md)