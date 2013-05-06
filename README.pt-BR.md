Webdevelopment :: Regras de Desenvolvimento :: Caminho para o Sucesso
======================

###1. Aplicação como Módulo
  * Mantenha sua aplicação simples de exportar
  * Evite utilizar variáveis de ambiente para os paths (caminhos) do sistema;
  * NÃO crie regras para o path dos arquivos no sistemas, mantenha sua aplicação simples
e baseie a localização dos arquivos a partir do diretório base da aplicação.


###2. Testes Unitários
  * Sempre aplique teste unitários durante o desenvolvimento (cobertura > 85%)


###3. Padrões de Projeto
  * Utilize padrões de projeto para solucionar seus problemas de arquitetura
  * Siga as conversões ORM e MV*
  * Desenvolva TDD (Test-driven development) ou BDD (behavion-driven development)


###4. Optimização Front-end
  * Javascript é uma linguagem funcionar, beneficie-se disso
  * Minifique seus scripts/stylesheets
  * Não bloqueio o carregamento de seu navegador. Reduza as requisições HTTP
  * Carrege conteúdo de terceiros de maneira assíncrona
  * Utilize ferramentas de métrica (como PageSpeed e YSlow) para garantir a velocidade de seu website
  * Utilize CSS Sprites
  * Evite escrever HTML em seu Javascript, utilize uma Template Engine


###5. Cache
  * Ative o cache inteligente em seu servidor
  * Experimente o Varnish Cache


###6. Integração Contínua
  * Alcance o flxo de trabalho perfeito, utilize TravisCI em seu projeto (ou outro serviço de Integração Contínua bem documentado)


###7. Ferramentas de Desenvolvimento
  * Utilize os recursos que seu IDE (ou editor de textos) lhe oferece
  * Conheça ferramentas e plugins para facilitar seu trabalho


###8. Projetos Web
  * Siga Projetos no Github
  * Twitter Bootstrap
  * HTML5 Bolierplate
  * Normalize
  * Siga as Weekly News  


##Recursos

####[Javascript](http://jstherightway.com/)####
Escreva Javascript da maneira correta.

####[Browser Diet](http://browserdiet.com/)####
Guia definitivo de desempenho front-end.

####[Javascript/HTML5/BrazilJS Weekly](http://javascriptweekly.com/)####
E-mail semanal com notícias e artigos atualizados sobre Javascript.

####[Sublime Text](http://www.sublimetext.com/)####
O editor de texto que fará você se apaixonar.

####[GruntJS](http://gruntjs.com/getting-started) / [Yeoman](http://yeoman.io/)####
Em uma palavra: automatização. Execute tarefas como minificação, compilação, teste unitário, linting.

####[Intern](http://theintern.io/)####
Esqueça o estresse de testar sua aplicação Web (integrado com SauceLabs e Selenium).

####[LessCSS](http://lesscss.org/) / [Sass](http://sass-lang.com/)####
Linguagem Dinâmica de stylesheet.

####[estilo.js](http://nodejs.org/)####
Plataforma construida sobre a engine Javascript do chrome para construir aplicações de rede rápidas e escaláveis.

####[Npm](https://npmjs.org/)####
Repositório de aplicações Node.js

####[Template Engine Chooser](http://garann.github.io/template-chooser/)####
Escolha a Template Engine correta conforme a necessidade de seu projeto.
