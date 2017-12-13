Q&A do curso de ciência da computação - UFCG 
-----------------------------

O sistema de perguntas e respostas do curso de ciência da computação da UFCG é um fork do projeto [Q2A](http://www.question2answer.org/) com o **idioma PT-BR** e o tema [Donut](https://github.com/amiyasahu/Donut) já instalado, além do plugin [Registration-Blocker](https://github.com/amiyasahu/q2a-registration-blocker), para que apenas usuários com emails `@ccc.ufcg.edu.br` ou `@computacao.ufcg.edu.br` seja permitido ser cadastrados.

Deploy
-----------------------------

Para subir uma instância do Q&A do curso de ciência da computação basta executar o comando `docker-compose up -d`, caso queira modificar a porta ou o nome do container do banco de dados, será necessário alterar o arquivo `qa-config.php` também!
