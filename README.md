<h1>RELATÓRIO – LARAVEL</h1>
<img  src="https://cdn.discordapp.com/attachments/762851212193693696/1039754476736753745/laravel.png" >
<h2>Introdução</h2>
<h3>O Laravel é um framework que te dá um suporte na programação em PHP, com várias ferramentas e funcionalidades pré prontas que agilizam seu trabalho. Ele auxilia principalmente nas partes de permissionamento, controle de seções, autenticação, entre várias outras aplicações. O mesmo foi criado para os sistemas web que utilizam o padrão MVC. Além de todas essas vantagens, o Laravel também possui suporte para os bancos de dados: MySQL, PostgreSQL, SQLite, SQL Server.
<h2>O que é um framework?</h2>
<h3>No mundo de desenvolvimento de softwares, o termo ‘frameworks’ refere-se à biblioteca de arquivos que armazena diversas funções básicas. O objetivo do framework é fornecer uma fundação para que você desenvolva seus projetos mais eficientemente.</h3>
 
<h2>Instalação:</h2>
<h3>
- Primeiramente, para iniciarmos a instalação do framework, o usuário deve já possuir instalado na máquina o PHP atualizado (Para verificar se já tem é só digitar "php --version" no cmd, e comparar a versão que apareceu com a mais atualizada no site do PHP); 

- Após isso, o usuário deve baixar o Composer, que é um gerente de dependência de PHP, ele permite que você declare as bibliotecas que seu projeto necessita e ele gerencia (instala / atualiza) elas para você; 

- Após instalar o composer, caso seu php ainda não esteja reconhecido em qualquer lugar do seu computador, é bom você configurá-lo para executar em qualquer lugar (Talvez o passo 1 não funcione mas você tem o PHP instalado e não fez esse passo);

- E agora sim, para instalar o framework basta digitar no cmd "composer global require laravel/install";

- E pronto! Se seguiu o passo a passo certinho seu laravel está instalado, para confirmar é só digitar "laravel --version" no cmd e conferir se apareceu sua última versão.
</h3>

<h2>Getting Started:</h2>
<h3>Após a instalação do framework, para se criar um primeiro projeto basta digitar o comando no diretório onde deseja criar o projeto "composer create-project laravel/laravel nome-da-pasta". Quando criamos o pprojeto nos deparamos com as seguintes pastas:</h3>

<img  src="https://cdn.discordapp.com/attachments/762851212193693696/1040800831664041984/image.png" >

<h3>
Diretório “app” - nele temos todos arquivos de nossa aplicação, podemos ver vários outros diretórios, mas iremos focar no diretório Http, pois nele temos o nosso arquivo routes.php, que é onde definimos todas as rotas de nossa aplicação. Temos também vários diretórios, entre eles, o “Controllers”, que é onde ficam todos os controllers de nossa aplicação.

Diretório config - onde configuramos todo nosso projeto. Nele temos o arquivo app.php, que é onde podemos configurar várias variáveis de nossa aplicação como local, fuso-horário, os providers e definir os aliases de nossa aplicação. Ainda no diretório config temos o arquivo database.php que é onde definimos todas as configurações sobre a conexão com o Banco de Dados. Ainda temos vários outros arquivos como o mail.php para definir configurações de e-mail de nossa aplicação;

Diretório database - onde definimos três tipos de arquivos importantes:
o Migrations: uma das ferramentas mais poderosas do Laravel para definir, através de arquivos PHP, como nosso Banco de Dados deve ser criado. Através do Artisan, que é a interface de linha de comando do Laravel, criamos, alteramos e excluímos tabelas do nosso Banco de Dados de forma fácil, rápida e intuitiva;
o Seeds: com esses arquivos podemos popular as tabelas do Banco de Dados com os dados que queremos para testes de forma fácil e rápida;
o Factories: essa ferramenta foi introduzida na versão 5.1 do Framework, para popular as tabelas do Banco de Dados com dados criados de forma automática e randômica, permitindo incluir uma grande massa de dados de forma bem rápida para criação de testes;

Diretório “public” - possui os arquivos .htaccess e index.php, que é o roteador de nossa aplicação. Ele recebe as requisições, as trata através do kernel e retorna para os usuários as respostas.

Diretório “resources” - nele temos três diretórios importantes:
o Assets: usado para armazenarmos todos arquivos de estilo (CSS, LESS, SASS, etc.), scripts (JavaScript, etc.), imagens e outros recursos necessários para nossa aplicação
o Lang: usado para armazenarmos os arquivos de tradução para nossa aplicação;
o Views: usado para armazenar os arquivos de nossa camada de visualização;

Arquivo “.env” - nele definimos várias configurações de nossa aplicação, como os dados de configuração da conexão do banco de dados e a configuração de e-mails.
 
</h3>
 
<h3>O Laravel é bastante utilizado por dev's no cotidiano pois torna mais fácil de se fazer sites que possuem "2 telas", que no caso seria uma tela pública que todos os usuários veriam e uma tela apenas para administradores acessarem</h3>
 
 <h2>Ferramentas Similares:</h2>
 
 <h3>SPRING BOOT</h3>
 <h3>O Spring Boot é um framework Java  que tem como objetivo facilitar esse processo em aplicações Java. Consequentemente, ele traz mais agilidade para o processo de desenvolvimento, uma vez que devs conseguem reduzir o tempo gasto com as configurações iniciais.
Com o Spring Boot conseguimos abstrair e facilitar a configuração de, por exemplo:

Servidores; 
Gerenciamento de dependências;
Configurações de bibliotecas;
Métricas & health checks;
  
Para realizar todo esse processo o Spring Boot utiliza um conceito chamado convenção sobre configuração.
Mas o que isso significa? Significa que é uma ferramenta que decide para você a melhor forma de se fazer algo. É o que chamamos de ferramenta opinativa, ela toma as decisões no nosso lugar baseado em convenções, aplicando configurações padrões e facilitando o trabalho.
No entanto ela não é inflexível e ainda permite uma configuração diferente da default caso o usuário assim deseje.
Uma das maiores vantagens que o Spring Boot trouxe ao desenvolvimento é que toda essa configuração não necessita mais ser realizada pelos temidos XMLs, embora ele ainda suporte esse tipo de configuração.  A maior parte da configuração pode ser feita de forma programática via anotações.
 Uma das maiores vantagens que o Spring Boot trouxe ao desenvolvimento é que toda essa configuração não necessita mais ser realizada pelos temidos XMLs, embora ele ainda suporte esse tipo de configuração.  A maior parte da configuração pode ser feita de forma programática via anotações.</h3>
