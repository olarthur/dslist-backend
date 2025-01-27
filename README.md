# Projeto-Evento Intensivão Java Spring
### Projeto: Listas de Jogos

## Sobre o Projeto
O projeto foi desenvolvido durante o evento Semana Intensivão Java Spring, organizado pelo Professor Nelio da comunidade DevSuperior.
Nele é proposto disponibilizar uma API comunicável com um banco de dados, onde armazena uma lista de jogos separadas por 
tipos, a API fornece a lógica e regras de negócio onde em uma lista de jogos é possível reorganizar a mesma conforme a 
requisição do usuário.

## Funcionalidades
- **Busca pelo ID:** Obtém a lista com o ID e nome do jogo.<br>
- **Busca breve de jogos:** Obtém a lista de jogos com uma pequena descrição.<br>
- **Busca todos os jogos:** Obtém a lista de jogos com a descrição completa.<br>
- **Mudança de posição:** Muda a posição de um jogo na lista e altera o banco de dados.<br>


## Tecnologias Utilizadas
- **Linguagem:** Java. 
- **Framework:** Spring Boot.
- **Gerenciamento de Depedência:** Maven.
- **Banco de dados:** H2 e Postgres.
- **Ferramenta de Teste:** Postman

## Modelo de Domínio

<div>
<img src="https://raw.githubusercontent.com/devsuperior/java-spring-dslist/main/resources/dslist-model.png">
</div>

## Assuntos abordados
- **Conceitos**
- **Estruturação de projeto Spring Rest**
- **Entidades e ORM**
- **Database seeding**
- **Padrão camadas**
- **Controller, service, repository**
- **Relacionamentos N-N, classe de associação**
- **Consultas SQL nativo**
- **Perfis de projeto**
- **Ambiente local com Docker Compose**
- **Processo de homologação local**
- **Design e implementação de endpoint**
- **Verbo HTTP e idempotência**