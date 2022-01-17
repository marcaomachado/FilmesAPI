# Construindo uma API Rest com .Net 5

## Programas

### Visual Studio : https://visualstudio.microsoft.com/pt-br/downloads/


### MySql : https://dev.mysql.com/downloads/windows/installer/5.7.html
#### Instalando o MySql:
- Abrir o executavel
- Selecionar Custom
- Marcar somente as opções da imagem abaixo

![image](https://user-images.githubusercontent.com/59896803/149529042-bf4b1720-c079-4516-8629-4be1e81d20d5.png)
- Next, Execute, Next... 
- Definir Login e Senha
- Next... Finish.


### Postman : https://www.postman.com/downloads/


## Pacotes Necessários e como instalá-los
No visual studio vá em:
  - Ferramentas
  - Gerenciados de Pacotes do NuGet
  - Gerenciar Pacotes do NuGet para a Solução...
  - Procurar:
    1. Microsoft.EntityFrameworkCore
    2. Microsoft.EntityFrameworkCore.Tools
    3. MySql.EntityFrameworkCore
    4. Automapper.extensions.microsoft.dependencyinjection


## Fazendo Migrations:
No visual studio vá em:
  - Ferramentas
  - Gerenciados de Pacotes do NuGet
  - Console do Gerenciador de Pacotes:
    - Add-Migration AlgumNomeParaEssaAção;
    - Update-Database
