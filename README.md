📚 README: Agenda Inteligente de Vistorias
Este repositório contém o código-fonte do sistema de Agenda Inteligente de Vistorias, um projeto com arquitetura monolítica baseada em Views.

Acesse: https://agenda-vistoria-frontend-web.onrender.com

🌟 Visão Geral do Projeto
O sistema é uma aplicação web de gerenciamento de vistorias, clientes e obras, utilizando o framework Spring Boot para o backend e JDBC direto para a comunicação com o banco de dados PostgreSQL.

Tecnologias Utilizadas
Arquitetura: Monolítica baseada em MVC (Model-View-Controller)

Backend: Java 21, Spring Boot 3.x

Controle de Dependências: Apache Maven

Banco de Dados: PostgreSQL Server (Versão 15 ou superior)

Persistência: Spring JDBC (Uso de JdbcTemplate para consultas e manipulação direta de SQL).

Templates (View): Thymeleaf (Renderização de HTML).

Utilitários: Lombok.

🛠️ Pré-requisitos
Para configurar e rodar este projeto localmente:

Java Development Kit (JDK): Versão 21.0.1 ou superior.

PostgreSQL Server: Versão 15 ou superior.

✨ Principais Funcionalidades Atuais
O sistema, em sua fase atual, oferece as seguintes funcionalidades principais:

Cadastro de Clientes:

Registro e manutenção de uma base de dados completa de clientes.

Informações chave: Nome/Razão Social, Contacto, Endereço.

Listagem de Clientes:

Visualização clara e organizada de todos os clientes cadastrados.

Cadastro de Obras por Cliente:

Associação direta de múltiplos projetos (obras) a um cliente específico.

Informações chave da Obra: Título do Projeto, Localização, Status Inicial.

Listagem de Obras:

Capacidade de listar todas as obras em andamento ou concluídas, filtradas por cliente.
