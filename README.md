# Projeto Cafeteria ☕️

Bem-vindo ao **Projeto Cafeteria**! Este é um sistema desenvolvido em **.NET** com **C#**, projetado para gerenciar uma cafeteria, incluindo pedidos, produtos e outros aspectos.

---

## 📋 Funcionalidades

- **Gerenciamento de Pedidos:** Controle completo dos pedidos dos clientes.
- **Cadastro de Produtos:** Registre e edite os produtos disponíveis na cafeteria.
- **Interface MVC:** Estrutura baseada no padrão **Model-View-Controller** para facilitar a manutenção.
- **Banco de Dados Integrado:** Utiliza **Entity Framework** para gerenciar dados e migrações.

---

## ⚙️ Requisitos

Antes de começar, certifique-se de que os seguintes requisitos estão instalados em sua máquina:

- [SDK .NET 6.0 ou superior](https://dotnet.microsoft.com/download)
- [Visual Studio 2022](https://visualstudio.microsoft.com/) (ou outro editor com suporte a .NET e C#)
- Banco de Dados (SQL Server, ou outro configurado no projeto)
- Git (para clonar o repositório)

---

## 🚀 Como executar o projeto

Siga os passos abaixo para configurar e executar o projeto em sua máquina:

### 1. Clonar o repositório

Use o seguinte comando no terminal para clonar o repositório:

```bash
git clone https://github.com/seu-usuario/projeto-cafeteria.git
```
Entre na pasta:
```bash
cd Cafeteria
```
### 2. Restaurar Pacotes

Execute o seguinte comando para restaurar as dependência do projeto:
```bash
dotnet restore
```

### 3. Configurar o Bancod de Dados
- Acesse o arquivo appsettings.json na pasta raiz do projeto
- Configurea string de conexão com o banco de dados:
```bash
"ConnectionStrings": {
  "DefaultConnection": "Server=SEU_SERVIDOR;Database=NomeDoBanco;Trusted_Connection=True;MultipleActiveResultSets=true"
}
```

### 4. Aplicar Migrações

Crie ou atualize o banco de dados usando as migrações
```bash
dotnet ef database update
```

### 5. Executar o Projeto
Inicie o servidor com o comando:
```bash
dotnet run
```
O projeto estará disponivel em: http://localhost:5000

---

## 📂 Estrutura do Projeto

- Controllers/: Contém os controladores responsáveis pela lógica de negócios.
- Models/: Classes que representam os dados do domínio.
- Views/: Arquivos de interface que exibem informações ao usuário.
- Migrations/: Scripts para gerenciar a evolução do banco de dados.
- wwwroot/: Arquivos estáticos como CSS, JS e imagens.

---

## 🛠 Tecnologias Utilizadas
As principais tecnologias utilizadas no desenvolvimento do projeto são:

- .NET 6.0: Framework principal para o desenvolvimento da aplicação.
- Entity Framework Core: ORM para gerenciamento do banco de dados.
- C#: Linguagem de programação.
- Bootstrap: Para estilização das interfaces.
- SQL Server: Banco de dados relacional utilizado no projeto.


### **Explicação**
- Este arquivo README.md cobre todas as áreas importantes: requisitos, execução, funcionalidades, estrutura.


