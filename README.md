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

#### Deploy na Azure
<img width="1327" height="518" alt="DeployMvcAzure" src="https://github.com/user-attachments/assets/6c295311-4991-4857-a986-c5e1ed6c3603" />

#### Aplicação x Banco de Dados Azure
 <img width="1237" height="656" alt="DeployMvcAzure2" src="https://github.com/user-attachments/assets/c766299c-e1d0-4f2a-9240-b0eee692f87e" />

#### Recursos Azure
<img width="1193" height="274" alt="DeployMvcAzure_recusos" src="https://github.com/user-attachments/assets/a4c1207f-c153-4755-98f1-036aa58ad3b7" />


