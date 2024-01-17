
# Utilizando Docker Compose para Executar uma Aplicação HTML em um Container Apache

## Descrição

O projeto tem como objetivo apresentar uma solução eficiente para o empacotamento e execução de aplicações web utilizando Docker Compose. Facilitando o desenvolvimento, distribuição e execução de aplicações web baseadas usando Docker e Docker Compose, o projeto consiste em criar um ambiente isolado e consistente para a execução de uma aplicação HTML simples em um servidor Apache, tudo isso empacotado em contêineres Docker.

## Funcionalidades:

- Docker Compose YML: foi criado um arquivo docker-compose.yml para definir e orquestrar o ambiente de contêineres. Este arquivo contém as configurações necessárias para iniciar um servidor Apache (httpd) e especifica o local onde os arquivos da aplicação HTML estarão.

- Configuração do Servidor Apache: O arquivo YML especifica a utilização do servidor Apache (httpd), garantindo que o ambiente seja configurado corretamente para hospedar aplicações web.

- Localização dos Arquivos da Aplicação: O Docker Compose YML define um volume para mapear o diretório local da aplicação HTML para o diretório correspondente dentro do contêiner Apache. Isso permite uma fácil atualização e modificação dos arquivos da aplicação sem a necessidade de parar o contêiner.

- A solução Docker Compose garante que a aplicação seja executada consistentemente em diferentes ambientes, independentemente do sistema operacional do host.

- A utilização de contêineres Docker isola a aplicação, evitando possíveis conflitos de dependências com o sistema operacional do host.