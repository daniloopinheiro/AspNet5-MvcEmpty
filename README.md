# Asp Net Na Versão 5 Em MVC Com Template Vazio

## Seguindo alguns procedimentos para implementação do projeto

- Criação de um template sln

$ dotnet new sln -o [nome da solução]
    
> obs. 
    
    -o ou --output 
    (O exemplo a seguir cria um arquivo .sln na pasta especificada, com o mesmo nome da pasta).

- Inserindo dentro do diretório sln um folder src

$ mkdir src

- Dentro do src, criação do projeto web mvc vazio

$ dotnet new web -n [nome do projeto]

> obs. 

    -n ou -name     
    (O exemplo a seguir cria um arquivo .sln na pasta atual, com o nome de arquivo especificado).

- Ajustando a classe Startup.cs para compreender as configurações do MVC.
- Criando uma classe HomeController dentro do diretório Controllers

$ touch HomeController.cs

- E dentro do diretório Views criação de uma pasta Home e criado a classe Index.cshtml (Raizor).

$ mkdir Home

- Descrevendo qualquer texto da Index.cshtml

Eu sou uma index, sendo chamada pela HomeController, estou dentro de uma pasta chamada Home, que esta na Views.

## Clone e Start da Aplicação

> Para iniciar projeto de forma mais limpa possível, execute o script shell.

$ sh run_app.sh

    Projeto finalizado.