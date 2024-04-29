# MVCponderada
ponderada de programação de arquitetura MVC

# Kauã Rodrigues - Turma 11 Grupo 03**

# Atividade Avaliativa de Programação Semana 01 - Arquitetura MVC**

Esta é a atividade avaliativa de programação da primeira semana do segundo módulo. O objetivo é desenvolver e apresentar um esboço detalhado da arquitetura MVC (Model-View-Controller) para o projeto em Sails.js que será realizado ao longo do módulo.

# Detalhes do Projeto**

- Nome do Projeto: MVT - Movimento Voluntário Transformador
- Descrição: A plataforma Web visa conectar organizações sociais e voluntários, facilitando o encontro entre os dois grupos. Assim, organizações poderão descobrir voluntários para participar em diversas iniciativas.
- Arquitetura: MVC (Model-View-Controller)
- Ferramenta para Diagramas: [draw.io](https://app.diagrams.net/)

# Sobre o framework Sails.js**

O Sails.js é o framework escolhido para o backend deste projeto. Ele é baseado na arquitetura MVC e é projetado para acelerar o desenvolvimento de aplicações, transformando meses de codificação em semanas. Além disso, o Sails.js oferece suporte facilitado à integração com diversas APIs.

# Funcionalidades Planejadas para a Plataforma**

Os usuários poderão se registrar como voluntários ou como organizações. Após o cadastro, poderão disponibilizar-se para atividades voluntárias ou buscar organizações que necessitam de voluntários. Além disso, será possível cadastrar eventos ou ações voluntárias e ter um perfil que exibe estatísticas de engajamento.

- Registro de usuário
- Disponibilização para atividades voluntárias
- Busca por atividades voluntárias
- Cadastro de eventos ou ações
- Exibição de estatísticas no perfil
- Estatísticas gerais da plataforma

# Sobre a Arquitetura MVC**

A arquitetura MVC divide a aplicação em três partes principais:

- **Views**: As páginas HTML que interagem diretamente com o usuário.
- **Controllers**: Controlam as interações entre o cliente e o servidor, contendo a lógica de negócios.
- **Models**: Gerenciam a comunicação com o banco de dados.


# Arquitetura do Projeto MVC
![image](https://github.com/kauarodriguessss/MVCponderada/assets/159058128/d8363943-3aa5-4313-b9f9-615f4849c537)

# Models:

No projeto, temos duas entidades principais:

- Usuários: Com atributos como ID, nome, email, senha, CEP, idade, horas de voluntariado, ações criadas e ações em que participa.
- Ações: Com atributos como ID, criador da ação, local, descrição, horas de trabalho e participantes.

# Views:

Planejamos cinco interfaces principais para a plataforma:

- Página inicial: Para apresentar o propósito da plataforma e engajar novos usuários.
- Cadastro: Para registrar novos usuários e coletar informações necessárias.
- Página principal: Para exibir oportunidades e perfis de voluntários, e permitir o cadastro de novas ações.
- Perfil do usuário: Para mostrar informações detalhadas do usuário e suas estatísticas.
- Página de ação: Para detalhar uma ação específica, possibilitando inscrições.

# Controllers:**

Os controladores desempenharão funções críticas na interação do usuário, como:

- Registro na plataforma
- Tornar-se disponível para voluntariado
- Inscrição em atividades
- Cadastro e atualização de ações
- Atualização de perfil
- Convite para participação em ações

# Infraestrutura e Justificativa:

Utilizaremos o PostgreSQL como sistema de banco de dados para armazenar todas as informações em formato de tabelas. O uso da arquitetura MVC e do framework Sails.js facilita a manutenção, testabilidade e escalabilidade do software, permitindo uma clara separação das responsabilidades e melhor organização do código.
