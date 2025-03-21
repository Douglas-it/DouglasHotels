# 🏨 DouglasHotels (Em Desenvolvimento)

> ⚠️ Este projeto ainda está em construção! Algumas funcionalidades podem estar incompletas ou sujeitas a mudanças.

> Um sistema de gestão de hotel desenvolvido em **C# e WPF**, permitindo reservas, cadastro de clientes e gerenciamento de quartos.

## 🚀 Tecnologias Utilizadas

Este projeto foi desenvolvido com as seguintes tecnologias:

- 🟢 **C#**
- 🟢 **WPF (Windows Presentation Foundation)**
- 🟢 **Entity Framework Core**
- 🟢 **SQLite / SQL Server** (dependendo da configuração)
- 🟢 **MVVM Architecture**


## 🔧 Como Rodar o Projeto Localmente

### 1️⃣ Clonar o repositório
```bash
git clone https://github.com/Douglas-it/DouglasHotels.git
cd DouglasHotels
```

### 2️⃣ Configurar o Banco de Dados
- Certifique-se de ter o **SQL Server** ou **SQLite** configurado.
- Atualize as configurações de conexão no arquivo `appsettings.json`.
- Rode as migrations para criar o banco de dados:
```bash
dotnet ef database update
```

### 3️⃣ Executar o Projeto
- Abra o projeto no **Visual Studio**.
- Selecione o projeto principal e clique em **Run**.

## ✅ Funcionalidades (Em Desenvolvimento)

- 🔹 Cadastro e gerenciamento de clientes
- 🔹 Controle de reservas e disponibilidade de quartos
- 🔹 Relatórios de ocupação do hotel
- 🔹 Login e autenticação de funcionários

## 🔜 Próximos Passos
- [ ] Criar sistema de pagamentos integrado
- [ ] Implementar dashboard administrativo
- [ ] Melhorar interface e experiência do usuário

## 🛠️ Contribuição

Caso queira contribuir:
1. Faça um fork do repositório.
2. Crie uma branch com a sua feature (`git checkout -b minha-feature`).
3. Commit suas mudanças (`git commit -m 'Adicionando nova feature'`).
4. Faça um push para a branch (`git push origin minha-feature`).
5. Abra um Pull Request 🚀.

## 📜 Licença

Este projeto está sob a licença MIT. Sinta-se à vontade para utilizá-lo e modificá-lo.


 
