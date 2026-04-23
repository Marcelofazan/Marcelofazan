MBA em Desenvolvimento FullStack pela IGTI e Analista de desenvolvimento de sistemas pela UNIP.

✨ Dicas especiais aqui no Git. 
  
API bash Linux 


cd /home/vboxuser/Projetos/API-EF10-JWT-main/SistemaERPOnlineForcaDeVendasAPI.WebAPI

dotnet tool install --global dotnet-ef

dotnet add package Microsoft.EntityFrameworkCore.Tools

dotnet add package Microsoft.EntityFrameworkCore.Design


## Efetuar Migrations

cd /home/vboxuser/Projetos/API-EF10-JWT-main/

dotnet add SistemaERPOnlineForcaDeVendasAPI.WebAPI package Microsoft.EntityFrameworkCore.Design

dotnet ef migrations add InitialCreate --project InfraEstrutura --startup-project SistemaERPOnlineForcaDeVendasAPI.WebAPI


## Run 

cd /home/vboxuser/Projetos/API-EF10-JWT-main/SistemaERPOnlineForcaDeVendasAPI.WebAPI

dotnet run 


# Erro de SSL nao criptografado 
SSL_ERROR_RX_RECORD_TOO_LONG

Altere 

https://localhost:5279/Swagger/index.html

Por 

http://localhost:5279/Swagger/index.html
