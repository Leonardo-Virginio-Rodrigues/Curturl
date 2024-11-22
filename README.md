# Encurtador de Links - Node.js e Express

Este é um projeto de um **Encurtador de Links** desenvolvido com **Node.js** e **Express**. O projeto utiliza o **SQLite3** para armazenar as URLs e suas estatísticas, e o **Sequelize** para interagir com o banco de dados de forma fácil e eficiente.

### Funcionalidades:
- **Gerar URLs Curtas**: Gera links curtos com 5 caracteres aleatórios (alfabeto + números).
- **Redirecionamento**: Ao acessar a URL curta, o usuário é redirecionado para a URL original.
- **Estatísticas**: Quando a URL curta é acessada, é possível visualizar as estatísticas de acessos e a data de cada acesso ao adicionar `/stats` ao final da URL curta.

## Tecnologias Utilizadas
- **Node.js**: Ambiente de execução JavaScript no servidor.
- **Express**: Framework minimalista para servidores web em Node.js.
- **SQLite3**: Banco de dados relacional leve utilizado para armazenar as URLs e suas estatísticas.
- **Sequelize**: ORM (Object-Relational Mapping) para facilitar a interação com o banco de dados SQLite3.

## Pré-requisitos

Antes de rodar o projeto, certifique-se de que você tem o **Node.js** instalado.
