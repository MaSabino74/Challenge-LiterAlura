<h1 align="center"> LiterAlura </h1>

# Projeto LiterAlura: Uma Biblioteca Virtual Interativa
O LiterAlura é um projeto de biblioteca virtual desenvolvido para o GitHub, focado na criação de um catálogo de livros dinâmico e funcional. Este desafio visa aprimorar habilidades em desenvolvimento back-end através da integração com uma API externa e da persistência de dados em um banco de dados relacional.
<br>
<br>
# Tecnologias Utilizadas
<br>
O projeto é construído utilizando uma stack robusta e amplamente utilizada no mercado:

Java: A linguagem de programação principal, conhecida por sua robustez e escalabilidade.
Spring Framework: Um dos frameworks mais populares para Java, facilitando o desenvolvimento de aplicações empresariais e web, incluindo funcionalidades como injeção de dependência e gerenciamento de transações.
PostgreSQL: Um poderoso sistema de gerenciamento de banco de dados relacional de código aberto, escolhido para garantir a persistência segura e eficiente dos dados dos livros.
Integração com a API Gutendex
Um dos pilares do LiterAlura é o consumo da API Gutendex. Esta API gratuita oferece acesso a um vasto repositório de dados de mais de 70 mil livros, permitindo ao projeto buscar, filtrar e exibir informações detalhadas sobre as obras. A integração com a Gutendex demonstra a capacidade de interagir com serviços externos e processar grandes volumes de dados.

# Objetivos do Projeto
<br>
O principal objetivo do desafio LiterAlura é proporcionar uma experiência prática e completa em:

# Consumo de API: 
<br>
Realizar requisições HTTP para a API Gutendex, processar as respostas e extrair os dados relevantes dos livros.
Persistência de Dados: Armazenar as informações obtidas da API no banco de dados PostgreSQL, garantindo que os dados sejam salvos e possam ser acessados posteriormente, mesmo após o encerramento da aplicação. Isso envolve a modelagem do banco de dados, a criação de entidades e o uso de ferramentas de ORM (Object-Relational Mapping) através do Spring Data JPA.
Este projeto é ideal para desenvolvedores que buscam consolidar seus conhecimentos em Java, Spring, integração de APIs e manipulação de bancos de dados relacionais, oferecendo uma base sólida para a construção de aplicações mais complexas.


# Funcionalidades do projeto

- `1 - Buscar livro pelo título`: Realizar a consulta diretamente na API e depois inserir o livro em no banco de dados
- `2 - Listar livros registrados`: Listar dados de todos os livros que inseridos
- `3 - Lista autores`: Listar os dados de cada autor
- `4 - Listar autores em determinado ano`: Listar autores na base de dados do ano determinado
- `5 - Listar livros em determinado idioma`: Quatro idiomas que você pode realizar a busca. Espanhol, inglês, francês e português
- `6 - Listar os 10 livros mais baixados`: Listar os 10 livros mais baixados no banco de dados
- `0 - Sair`: Sair da aplicação


# Contribuição
Este projeto foi desenvolvido como parte de um curso "Praticando Spring Boot: Challenge LiterAlura", mas contribuições são sempre bem-vindas! Se você tiver sugestões ou encontrar algum problema, sinta-se à vontade para abrir uma issue ou enviar um pull request.

Desenvolvido por Marcos Sabino

🔗 [Seu LinkedIn](https://www.linkedin.com/in/marcos-sabino-90b1b5a5/)  
🐙 [Seu GitHub](https://github.com/MaSabino74)
