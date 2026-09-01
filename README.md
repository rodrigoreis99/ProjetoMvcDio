## Projeto desenvolvido junto ao curso de C#


#### Criando MVC
> dotnet new mvc

#### Executar MVC
> dotnet watch run

#### Instalar pacotes EntityFramework (pacotes que devem ser instalados a cada projeto se necessário)
> dotnet add package Microsoft.EntityFrameworkCore.SqlServer

> dotnet add package Microsoft.EntityFrameworkCore.Design


#### Criando a migration (para criação de uma tabela no banco de dados)
> dotnet-ef migrations add CriacaoTabelaContato

#### Aplicar a migration
> dotnet ef database update 


<br>

___


#### Se ainda não instalou o pacote Entity Framework. (Só instala uma vez, sua instalação é feita na máquina e não no projeto)
> dotnet tool install --global dotnet-ef

#### Newtonsoft. JSON
> dotnet add package Newtonsoft.Json


#### Colocar "Encrypt=False" no final da conexão na ConnectionStrings
> "ConexaoPadrao" : "Server=localhost\\sqlexpress; Initial Catalog=AgendaMvc; Integrated Security=True; Encrypt=False"

