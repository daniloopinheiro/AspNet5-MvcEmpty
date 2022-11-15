# Asp Net Na Versão 5 Em MVC Com Template Vazio

## Seguindo alguns procedimetos para implementação do projeto

- Criação de um template sln

$ dotnet new sln -o [nome da solução]
    
> obs: -o ou --output (O exemplo a seguir cria um arquivo .sln na pasta especificada, com o mesmo nome da pasta).

- Inserindo dentro do diretorio sln um folder src

$ mkdir src

- Dentro do src, criacao do projeto web mvc vazio

$ dotnet new web -n [nome do projeto]

> obs: -n ou -name (O exemplo a seguir cria um arquivo .sln na pasta atual, com o nome de arquivo especificado).

- Ajustando a classe Startup.cs para compreender as configuracoes do MVC.
- Criando uma classes HomeController dentro do diretorio Controllers

$ touch HomeController.cs

- E dentro do diretorio Views criação de uma pasta Home e criado a classe Index.cshtml (Raizor).

$ mkdir Home

- Descrevendo qualquer testo da Index.cshtml

Eu sou uma index, sendo chamada pela HomeController, estou dentro de uma pasta chamada Home, que esta na Views.