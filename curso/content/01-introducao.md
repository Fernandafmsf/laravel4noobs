## Introdução 
Gosto muito da frase muitas vezes dita pelo nosso querido Daniel He4rt: 
- Laravel é magia!

E realmente, quanto mais você se aprofundar no Laravel, vai ver que parece **mesmo** magia. 

### Mas afinal de contas, o que é o Laravel?
O Laravel é simplesmente o que chamamos de **framework**. Criado por Taylor Otwell em 2011, tem foco em elegância, simplicidade e produtividade.

Ele nos dá toda uma estrutura para iniciar nossa aplicação Web, evitando que seja necessário criar e se preocupar com diversos detalhes, como roteamento, migrações de banco de dados, filas... 

O Laravel possui tudo embutido (ou é integrado facilmente).

**Curiosidade:** O nome “Laravel” foi inspirado em Cair Paravel, o castelo de Nárnia. A ideia era criar algo “nobre” para o PHP.

### Por que o Laravel? 
Além de muito poderoso, ele é um ótimo framework para **começar**. A comunidade é muito forte, possui muito conteúdo sobre e é possível integrar front com back apenas usando o Laravel. 

E para os desenvolvedores mais experientes, o framework oferece filas, eventos, schedules, listeners, injeção de dependencias e muito mais. De uma forma bem estruturada e nada verbosa. 

Algumas das ferramentas do Laravel: 
- Eloquent ORM: camada de banco de dados onde escrevemos consultas como se estivéssesmo falando com os objetos, sem precisar utilizar consultas nativas SQL. 

- Blade: Sistema de templates do Laravel, limpo, poderoso e fácil de aprender

- Segurança por padrão: Proteção CSRF, Hash de senhas, prevenção de SQL Injection via eloquent e etc. 

### Arquitetura básica 
Laravel segue o padrão MVC (Model-View-Controller), uma das arquiteturas mais populares para aplicações web. 

//adicionar imagem mvc aqui//

- Model: No laravel, as models representam, basicamente, uma tabela do banco de dados. Representa os dados e lógica do negócio. 

- View: É a camada de apresentação, o que o usuário vê. No Laravel usamos o Blade para criar as views. 

- Controller: É o intermediário, responsável por receber as requisições HTTP que vem das rotas, consultar as models se preciso e, então, retornar um view (ou JSON se for uma api).  

[Próximo: Instalação →](./02-instalacao.md)
