# Suporte Técnico
## Backend
Para o desenvolvimento do backend, optamos por construir uma API REST em .NET 9.0. Além da linguagem e do framework, utilizamos ferramentas essenciais como o Visual Studio como IDE, o Entity Framework como ORM e o PostgreSQL como banco de dados relacional.

### .NET & EntityFramework
A escolha do .NET 9.0 se deu pela afinidade e experiência da equipe, além da maturidade e robustez do ecossistema. Quanto ao ORM, a decisão foi natural: o Entity Framework é amplamente utilizado no desenvolvimento .NET e oferece uma comunicação consistente, segura e otimizada entre o sistema e o banco de dados.

Para gerenciamento das migrations, utilizamos a biblioteca Design, permitindo executar, reverter e ajustar versões estruturais do banco de maneira ágil. Isso foi especialmente importante devido ao curto prazo de desenvolvimento e às diversas alterações de modelagem ao longo do projeto. Nesse contexto, trabalhar com migrations proporcionou flexibilidade e segurança na evolução do banco de dados.

### Postgress
A escolha do banco PostgreSQL ocorreu por ser um projeto open source, estável e amplamente adotado no mercado. Além disso, o Entity Framework nos garante liberdade tecnológica: com poucas configurações é possível trocar o provedor de banco sem afetar o código de negócio.

Outras ferramentas também foram utilizadas ao longo do desenvolvimento, mas acreditamos que, inicialmente, não seja necessário detalhá-las aqui. Sinta-se à vontade para explorar o código e descobrir cada uma delas, essa é a grande vantagem de projetos open source.